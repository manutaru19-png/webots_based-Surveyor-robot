switch(command) {

    case 'F':   // Forward
        wb_motor_set_velocity(leftMotor, speed);
        wb_motor_set_velocity(rightMotor, speed);
        break;

    case 'B':   // Backward
        wb_motor_set_velocity(leftMotor, -speed);
        wb_motor_set_velocity(rightMotor, -speed);
        break;

    case 'L':   // Left
        wb_motor_set_velocity(leftMotor, -speed);
        wb_motor_set_velocity(rightMotor, speed);
        break;

    case 'R':   // Right
        wb_motor_set_velocity(leftMotor, speed);
        wb_motor_set_velocity(rightMotor, -speed);
        break;
        
}
