Class **Phalcon\\Db\\Profiler\\Item**
=====================================

This class identifies each profile in a Phalcon\\Db\\Profiler


Methods
-------

public  **setSQLStatement** (*string* $sqlStatement)

Sets the SQL statement related to the profile



public *string*  **getSQLStatement** ()

Returns the SQL statement related to the profile



public  **setSQLVariables** (*unknown* $sqlVariables)

Sets the SQL variables related to the profile



public *array*  **getSQLVariables** ()

Returns the SQL variables related to the profile



public  **setSQLBindTypes** (*unknown* $sqlBindTypes)

Sets the SQL bind types related to the profile



public *array*  **getSQLBindTypes** ()

Returns the SQL bind types related to the profile



public  **setInitialTime** (*int* $initialTime)

Sets the timestamp on when the profile started



public  **setFinalTime** (*int* $finalTime)

Sets the timestamp on when the profile ended



public *double*  **getInitialTime** ()

Returns the initial time in milseconds on when the profile started



public *double*  **getFinalTime** ()

Returns the initial time in milseconds on when the profile ended



public *double*  **getTotalElapsedSeconds** ()

Returns the total time in seconds spent by the profile



