# StationReportNotes
All the notes and password

Thingsboard Upload Standard:
{"Station":"Tin Shui Wai","Latitude":22.4477,"Longitude":114.00400000000002,"Status":"Police","Comment":"TSW hi comment here"}
;
The Station is selected, Lat and Long is generator on broswer side （Lookup table)
Status for them to choose: Safe/Danger/Police
Comment: A place for them to type everything

POST RESTful API:
curl -v -X POST -d "{"Station":"Tin Shui Wai","Latitude":22.4477,"Longitude":114.00400000000002,"Status":"Police","Comment":"TSW hi comment here"}" http://demo.thingsboard.io:80/api/v1/FI4Rvw0zDi4aHC99R8nr/telemetry --header "Content-Type:application/json"


============Thingsboard==========================
sethi@jembotbrodol.com
jembotbrodol

==========Github======================
sethi@jembotbrodol.com
sethijembotbrodol



Testing tools:
https://reqbin.com/
https://www.gps-coordinates.net/

DEMO:
https://reqbin.com/bqdozm7c  (TSW)
https://reqbin.com/tq4zd34r  (YL)

TODO:
Will add all the device on thingsboard and search all the GPS and post it here
