

#pragma config(Motor,  port2,           rightMotor,    tmotorNormal, openLoop, reversed)
#pragma config(Motor,  port3,           leftMotor,     tmotorNormal, openLoop)

task main()
{

  motor[rightMotor] = 0;
	motor[leftMotor]  = 0;
	wait1Msec(1000);

	motor[rightMotor] = 60;
	motor[leftMotor]  = 50;
	wait1Msec(1000);
}
