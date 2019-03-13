# Period-2-botball
//moving bunbun up for the WRU
motor(port#1, 100);
motor(port#2, 100);
msleep();

//claw to grab WRU
servo(port#1, servopos);
servo(port#2, servopos);
msleep();

//backing up
motor(port#1, -100);
motor(port#2, -100);
msleep();

//turning left to place WRU
motor(port#1, 100);
motor(port#2, -100);
msleep();

//going to middle and placing WRU
motor(port#1, 100);
motor(port#2, 100);
msleep();

//dropping the WRU
servo(port#1, servopos);
servo(port#2, servopos);
msleep();

//backing up a bit
motor(port#1, -100);
motor(port#2, -100);
msleep();

//turning right to face blue tape
motor(port#1,-100);
motor(port#2, 100);
msleep();

//moving onto blue tape
motor(port#1, 100);
motor(port#2, 100);
msleep();

//turning left to face poms
motor(port#1, 100);
motor(port#2, -100);
msleep();

//acvivate pom feeder
motor(port#3, -100);
motor(port#4, -100);
msleep();

//move forward collecting poms
motor(port#1, 100);
motor(port#2, 100);
msleep();

//move backward
motor(port#1, -100);
motor(port#2, -100);
msleep();

//turning right to face the edge
motor(port#1,-100);
motor(port#2, 100);
msleep();

//move forward towards edge
motor(port#1, 100);
motor(port#2, 100);
msleep();


motor(port#1, 100);
motor(port#2, 100);
msleep();

//claw to grab WRU
servo(port#1, servopos);
servo(port#2, servopos);
msleep();

//backing up
motor(port#1, -100);
motor(port#2, -100);
msleep();

//turning left to place WRU
motor(port#1, 100);
motor(port#2, -100);
msleep();

//going to middle and placing WRU
motor(port#1, 100);
motor(port#2, 100);
msleep();

//dropping the WRU
servo(port#1, servopos);
servo(port#2, servopos);
msleep();

//backing up a bit
motor(port#1, -100);
motor(port#2, -100);
msleep();

//turning right to face blue tape
motor(port#1,-100);
motor(port#2, 100);
msleep();

//moving onto blue tape
motor(port#1, 100);
motor(port#2, 100);
msleep();

//turning left to face poms
motor(port#1, 100);
motor(port#2, -100);
msleep();

//acvivate pom feeder
motor(port#3, -100);
motor(port#4, -100);
msleep();

//move forward collecting poms
motor(port#1, 100);
motor(port#2, 100);
msleep();

//move backward
motor(port#1, -100);
motor(port#2, -100);
msleep();

//turning right to face the edge
motor(port#1,-100);
motor(port#2, 100);
msleep();

//move forward towards edge
motor(port#1, 100);
motor(port#2, 100);
msleep(
