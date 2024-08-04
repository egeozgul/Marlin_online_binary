#define X_DRIVER_TYPE  A4988
#define Y_DRIVER_TYPE  A4988
#define Z_DRIVER_TYPE  A4988
#define E0_DRIVER_TYPE A4988
BAUDRATE 250000
BOARD_MKS_GEN_13
heatbed temp sensor disabled
#define DEFAULT_AXIS_STEPS_PER_UNIT   { 80, 80, 3200, 837}

#define X_BED_SIZE 550
#define Y_BED_SIZE 850
#define Z_MAX_POS 380

#define X_HOME_DIR 1
#define Y_HOME_DIR -1
#define Z_HOME_DIR -1

bilinear bed leveling

#define GRID_MAX_POINTS_X 5
#define GRID_MAX_POINTS_Y 5
