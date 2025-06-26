# utl-octave-matlab-deleting-rows-where-age-is-zero
octave matlab deleting rows where age is zero
    %let pgm=utl-octave-matlab-deleting-rows-where-age-is-zero;

    %stop_submission;

    octave matlab deleting rows where age is zero

    github
    https://tinyurl.com/4k2usd69
    https://github.com/rogerjdeangelis/utl-octave-matlab-deleting-rows-where-age-is-zero

    related to
    stackoverflow matlab
    https://tinyurl.com/2z829ab7
    https://stackoverflow.com/questions/2635967/how-to-delete-zero-components-in-a-vector-in-matlab

    sql_create_insert function
    https://tinyurl.com/2r9ekpn8
    https://github.com/rogerjdeangelis/utl-how-to-store-octave-matlab-objects-in-external-files-for-later-use-with-octave-r-and-python

    /***********************************************************************************************************************/
    /*   INPUT                               | PROCESS                                               | OUTPUT              */
    /* local dbtable students                | /*---- delete the entire sqlite database ----*/       | RESULT (DBTABLE     */
    /* 6x3 table                             | %utlfkil(d:/sqlite/have.db);                          | Name   Age  Score   */
    /*                                       |                                                       | _____  ___  _____   */
    /* Name    Score   Age                   | %utl_mbegin;                                          |                     */
    /* _______ _____   ___                   | parmcards4;                                           | Alice  25   88.5    */
    /*                                       |                                                       | Bob    30   92      */
    /* Alice   88.5    25                    | pkg load sqlite                                       | Diana  28   85      */
    /* Bob     92      30                    |                                                       | Frank  40   87      */
    /* Charlie 79.5     0 delete             | db = sqlite("d:/sqlite/have.db","create");            |                     */
    /* Diana   85      28                    | execute(db, 'select load_extension("d:/dll/sqlean")');|                     */
    /* Eve     91.5     0 delete             |                                                       |                     */
    /* Frank   87      40                    | Name={"Alice";"Bob";"Charlie";"Diana";"Eve";"Frank"}; |                     */
    /*                                       | Age=[25;30;0;28;0;40];                                |                     */
    /*                                       | Score=[88.5;92.0;79.5;85.0;91.5;87.0];                |                     */
    /* %utl_mbegin;                          | students=dbtable(Name,Age,Score);                     |                     */
    /* parmcards4;                           | disp(students)                                        |                     */
    /* Name={"Alice";"Bob";"Charlie";        |                                                       |                     */
    /* "Diana";"Eve";"Frank"};               | sql_create_insert(db,students,"want")                 |                     */
    /* Age=[25;30;0;28;0;40];                |                                                       |                     */
    /* Score=[88.5;92.0;79.5;85.0;91.5;87.0];| result = fetch(                                       |                     */
    /* students=dbtable(Name,Age,Score);     |   db                                                  |                     */
    /* disp(students)                        |  ,'select * from want where age <> 0');               |                     */
    /* ;;;;                                  |                                                       |                     */
    /* %utl_mend;                            | disp(result)                                          |                     */
    /*                                       | close(db);                                            |                     */
    /*                                       | ;;;;                                                  |                     */
    /*                                       | %utl_mend;                                            |                     */
    /***********************************************************************************************************************/

    /*              _
      ___ _ __   __| |
     / _ \ `_ \ / _` |
    |  __/ | | | (_| |
     \___|_| |_|\__,_|

