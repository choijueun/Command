### Profile 설정

    SELECT @@profiling;

0: OFF

1: ON

    SET profiling = 1;
    SET @@profiling_history_size = 100;

profiling_history_size default: 15

min~max: 0 to 100