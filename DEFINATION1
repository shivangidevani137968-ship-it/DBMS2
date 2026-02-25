Definition 1:

Write a PL/SQL block which accepts measurement in feet and displays it
in cm, inch and meter

DECLARE

feet NUMBER:=&amp;feet;
cm NUMBER;
inch NUMBER;
meter NUMBER;

BEGIN

inch := feet * 12;
cm := inch * 2.54;
meter := feet * 0.3048;
DBMS_OUTPUT.PUT_LINE(&#39;Measurement in Feet : &#39; || feet);
DBMS_OUTPUT.PUT_LINE(&#39;Measurement in Inches: &#39; || inch);
DBMS_OUTPUT.PUT_LINE(&#39;Measurement in CM : &#39; || cm);
DBMS_OUTPUT.PUT_LINE(&#39;Measurement in Meter : &#39; || meter);

END;
/
