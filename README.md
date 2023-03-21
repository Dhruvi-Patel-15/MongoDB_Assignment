# MongoDB_Assignment

* By simply giving the command ‘use dbname’ we can create the database in Mongodb.<br>
* After that we need to make a collection which is analogous to tables in SQL.<br>
* For the sake of the practical, I have created database called MongoDB_Assignment and collection called datas.<br>

### Question 1
>**Batch Create with minimum 100 records in MongoDb (create batch).**<br><br>
>*db.datas.insertMany([<br>
>{ "_id" : "01001", "city" : "AGAWAM", "loc" : [ -72.622739, 42.070206 ], "pop" : 15338, "state" : "MA" },<br>
>{ "_id" : "01002", "city" : "CUSHMAN", "loc" : [ -72.51564999999999, 42.377017 ], "pop" : 36963, "state" : "MA" },<br>
>{ "_id" : "01005", "city" : "BARRE", "loc" : [ -72.10835400000001, 42.409698 ], "pop" : 4546, "state" : "MA" },<br>
>{ "_id" : "01007", "city" : "BELCHERTOWN", "loc" : [ -72.41095300000001, 42.275103 ], "pop" : 10579, "state" : "MA" },<br>
>{ "_id" : "01008", "city" : "BLANDFORD", "loc" : [ -72.936114, 42.182949 ], "pop" : 1240, "state" : "MA" },<br>
>{ "_id" : "01010", "city" : "BRIMFIELD", "loc" : [ -72.188455, 42.116543 ], "pop" : 3706, "state" : "MA" },<br>
>{ "_id" : "01011", "city" : "CHESTER", "loc" : [ -72.988761, 42.279421 ], "pop" : 1688, "state" : "MA" },<br>
>{ "_id" : "01012", "city" : "CHESTERFIELD", "loc" : [ -72.833309, 42.38167 ], "pop" : 177, "state" : "MA" },<br>
>{ "_id" : "01013", "city" : "CHICOPEE", "loc" : [ -72.607962, 42.162046 ], "pop" : 23396, "state" : "MA" },<br>
>{ "_id" : "01020", "city" : "CHICOPEE", "loc" : [ -72.576142, 42.176443 ], "pop" : 31495, "state" : "MA" },<br>
>{ "_id" : "01022", "city" : "WESTOVER AFB", "loc" : [ -72.558657, 42.196672 ], "pop" : 1764, "state" : "MA" },<br>
>{ "_id" : "01026", "city" : "CUMMINGTON", "loc" : [ -72.905767, 42.435296 ], "pop" : 1484, "state" : "MA" },<br>
>{ "_id" : "01027", "city" : "MOUNT TOM", "loc" : [ -72.67992099999999, 42.264319 ], "pop" : 16864, "state" : "MA" },<br>
>{ "_id" : "01028", "city" : "EAST LONGMEADOW", "loc" : [ -72.505565, 42.067203 ], "pop" : 13367, "state" : "MA" },<br>
>{ "_id" : "01030", "city" : "FEEDING HILLS", "loc" : [ -72.675077, 42.07182 ], "pop" : 11985, "state" : "MA" },<br>
>{ "_id" : "01031", "city" : "GILBERTVILLE", "loc" : [ -72.19858499999999, 42.332194 ], "pop" : 2385, "state" : "MA" },<br>
>{ "_id" : "01032", "city" : "GOSHEN", "loc" : [ -72.844092, 42.466234 ], "pop" : 122, "state" : "MA" },<br>
>{ "_id" : "01033", "city" : "GRANBY", "loc" : [ -72.52000099999999, 42.255704 ], "pop" : 5526, "state" : "MA" },<br>
>{ "_id" : "01034", "city" : "TOLLAND", "loc" : [ -72.908793, 42.070234 ], "pop" : 1652, "state" : "MA" },<br>
>{ "_id" : "01035", "city" : "HADLEY", "loc" : [ -72.571499, 42.36062 ], "pop" : 4231, "state" : "MA" },<br>
>{ "_id" : "01036", "city" : "HAMPDEN", "loc" : [ -72.43182299999999, 42.064756 ], "pop" : 4709, "state" : "MA" },<br>
>{ "_id" : "01038", "city" : "HATFIELD", "loc" : [ -72.61673500000001, 42.38439 ], "pop" : 3184, "state" : "MA" },<br>
>{ "_id" : "01039", "city" : "HAYDENVILLE", "loc" : [ -72.70317799999999, 42.381799 ], "pop" : 1387, "state" : "MA" },<br>
>{ "_id" : "01040", "city" : "HOLYOKE", "loc" : [ -72.626193, 42.202007 ], "pop" : 43704, "state" : "MA" },<br>
>{ "_id" : "01050", "city" : "HUNTINGTON", "loc" : [ -72.873341, 42.265301 ], "pop" : 2084, "state" : "MA" },<br>
>{ "_id" : "01053", "city" : "LEEDS", "loc" : [ -72.70340299999999, 42.354292 ], "pop" : 1350, "state" : "MA" },<br>
>{ "_id" : "01054", "city" : "LEVERETT", "loc" : [ -72.499334, 42.46823 ], "pop" : 1748, "state" : "MA" },<br>
>{ "_id" : "01056", "city" : "LUDLOW", "loc" : [ -72.471012, 42.172823 ], "pop" : 18820, "state" : "MA" },<br>
>{ "_id" : "01057", "city" : "MONSON", "loc" : [ -72.31963399999999, 42.101017 ], "pop" : 8194, "state" : "MA" },<br>
>{ "_id" : "01060", "city" : "FLORENCE", "loc" : [ -72.654245, 42.324662 ], "pop" : 27939, "state" : "MA" },<br>
>{ "_id" : "01068", "city" : "OAKHAM", "loc" : [ -72.051265, 42.348033 ], "pop" : 1503, "state" : "MA" },<br>
>{ "_id" : "01069", "city" : "PALMER", "loc" : [ -72.328785, 42.176233 ], "pop" : 9778, "state" : "MA" },<br>
>{ "_id" : "01070", "city" : "PLAINFIELD", "loc" : [ -72.918289, 42.514393 ], "pop" : 571, "state" : "MA" },<br>
>{ "_id" : "01071", "city" : "RUSSELL", "loc" : [ -72.840343, 42.147063 ], "pop" : 608, "state" : "MA" },<br>
>{ "_id" : "01072", "city" : "SHUTESBURY", "loc" : [ -72.421342, 42.481968 ], "pop" : 1533, "state" : "MA" },<br>
>{ "_id" : "01073", "city" : "SOUTHAMPTON", "loc" : [ -72.719381, 42.224697 ], "pop" : 4478, "state" : "MA" },<br>
>{ "_id" : "01075", "city" : "SOUTH HADLEY", "loc" : [ -72.581137, 42.237537 ], "pop" : 16699, "state" : "MA" },<br>
>{ "_id" : "01077", "city" : "SOUTHWICK", "loc" : [ -72.770588, 42.051099 ], "pop" : 7667, "state" : "MA" },<br>
>{ "_id" : "01080", "city" : "THREE RIVERS", "loc" : [ -72.362352, 42.181894 ], "pop" : 2425, "state" : "MA" },<br>
>{ "_id" : "01081", "city" : "WALES", "loc" : [ -72.20459200000001, 42.062734 ], "pop" : 1732, "state" : "MA" },<br>
>{ "_id" : "01082", "city" : "WARE", "loc" : [ -72.258285, 42.261831 ], "pop" : 9808, "state" : "MA" },<br>
>{ "_id" : "01085", "city" : "MONTGOMERY", "loc" : [ -72.754318, 42.129484 ], "pop" : 40117, "state" : "MA" },<br>
>{ "_id" : "01089", "city" : "WEST SPRINGFIELD", "loc" : [ -72.641109, 42.115066 ], "pop" : 27537, "state" : "MA" },<br>
>{ "_id" : "01092", "city" : "WEST WARREN", "loc" : [ -72.203639, 42.20734 ], "pop" : 4441, "state" : "MA" },<br>
>{ "_id" : "01095", "city" : "WILBRAHAM", "loc" : [ -72.446415, 42.124506 ], "pop" : 12635, "state" : "MA" },<br>
>{ "_id" : "01096", "city" : "WILLIAMSBURG", "loc" : [ -72.77798900000001, 42.408522 ], "pop" : 2295, "state" : "MA" },<br>
>{ "_id" : "01098", "city" : "WORTHINGTON", "loc" : [ -72.931427, 42.384293 ], "pop" : 877, "state" : "MA" },<br>
>{ "_id" : "01103", "city" : "SPRINGFIELD", "loc" : [ -72.588735, 42.1029 ], "pop" : 2323, "state" : "MA" },<br>
>{ "_id" : "01104", "city" : "SPRINGFIELD", "loc" : [ -72.577769, 42.128848 ], "pop" : 22115, "state" : "MA" },<br>
>{ "_id" : "01105", "city" : "SPRINGFIELD", "loc" : [ -72.578312, 42.099931 ], "pop" : 14970, "state" : "MA" },<br>
>{ "_id" : "01106", "city" : "LONGMEADOW", "loc" : [ -72.5676, 42.050658 ], "pop" : 15688, "state" : "MA" },<br>
>{ "_id" : "01107", "city" : "SPRINGFIELD", "loc" : [ -72.606544, 42.117907 ], "pop" : 12739, "state" : "MA" },<br>
>{ "_id" : "01108", "city" : "SPRINGFIELD", "loc" : [ -72.558432, 42.085314 ], "pop" : 25519, "state" : "MA" },<br>
>{ "_id" : "01109", "city" : "SPRINGFIELD", "loc" : [ -72.554349, 42.114455 ], "pop" : 32635, "state" : "MA" },<br>
>{ "_id" : "01118", "city" : "SPRINGFIELD", "loc" : [ -72.527445, 42.092937 ], "pop" : 14618, "state" : "MA" },<br>
>{ "_id" : "01119", "city" : "SPRINGFIELD", "loc" : [ -72.51211000000001, 42.12473 ], "pop" : 13040, "state" : "MA" },<br>
>{ "_id" : "01128", "city" : "SPRINGFIELD", "loc" : [ -72.48890299999999, 42.094397 ], "pop" : 3272, "state" : "MA" },<br>
>{ "_id" : "01129", "city" : "SPRINGFIELD", "loc" : [ -72.487622, 42.122263 ], "pop" : 6831, "state" : "MA" },<br>
>{ "_id" : "01151", "city" : "INDIAN ORCHARD", "loc" : [ -72.505048, 42.153225 ], "pop" : 8702, "state" : "MA" },<br>
>{ "_id" : "01201", "city" : "PITTSFIELD", "loc" : [ -73.24708800000001, 42.453086 ], "pop" : 50655, "state" : "MA" },<br>
>{ "_id" : "01220", "city" : "ADAMS", "loc" : [ -73.117225, 42.622319 ], "pop" : 9901, "state" : "MA" },<br>
>{ "_id" : "01222", "city" : "ASHLEY FALLS", "loc" : [ -73.320195, 42.059552 ], "pop" : 561, "state" : "MA" },<br>
>{ "_id" : "01223", "city" : "BECKET", "loc" : [ -73.12032499999999, 42.359363 ], "pop" : 1070, "state" : "MA" },<br>
>{ "_id" : "01225", "city" : "CHESHIRE", "loc" : [ -73.15796400000001, 42.561059 ], "pop" : 3094, "state" : "MA" },<br>
>{ "_id" : "01226", "city" : "DALTON", "loc" : [ -73.160259, 42.475046 ], "pop" : 7357, "state" : "MA" },<br>
>{ "_id" : "01230", "city" : "GREAT BARRINGTON", "loc" : [ -73.36065000000001, 42.195922 ], "pop" : 10603, "state" : "MA" },<br>
>{ "_id" : "01235", "city" : "PERU", "loc" : [ -73.092433, 42.434604 ], "pop" : 2559, "state" : "MA" },<br>
>{ "_id" : "01236", "city" : "HOUSATONIC", "loc" : [ -73.374544, 42.265296 ], "pop" : 802, "state" : "MA" },<br>
>{ "_id" : "01237", "city" : "HANCOCK", "loc" : [ -73.24873700000001, 42.541961 ], "pop" : 2328, "state" : "MA" },<br>
>{ "_id" : "01238", "city" : "LEE", "loc" : [ -73.231696, 42.298994 ], "pop" : 6916, "state" : "MA" },<br>
>{ "_id" : "01240", "city" : "LENOX", "loc" : [ -73.271322, 42.364241 ], "pop" : 5001, "state" : "MA" },<br>
>{ "_id" : "01243", "city" : "MIDDLEFIELD", "loc" : [ -73.006226, 42.34795 ], "pop" : 384, "state" : "MA" },<br>
>{ "_id" : "01245", "city" : "WEST OTIS", "loc" : [ -73.213452, 42.187847 ], "pop" : 329, "state" : "MA" },<br>
>{ "_id" : "01247", "city" : "CLARKSBURG", "loc" : [ -73.10999, 42.69865 ], "pop" : 19054, "state" : "MA" },<br>
>{ "_id" : "01253", "city" : "OTIS", "loc" : [ -73.082093, 42.18988 ], "pop" : 1060, "state" : "MA" },<br>
>{ "_id" : "01254", "city" : "RICHMOND", "loc" : [ -73.364457, 42.378398 ], "pop" : 1134, "state" : "MA" },<br>
>{ "_id" : "01255", "city" : "SANDISFIELD", "loc" : [ -73.116285, 42.109429 ], "pop" : 651, "state" : "MA" },<br>
>{ "_id" : "01256", "city" : "SAVOY", "loc" : [ -73.023281, 42.576964 ], "pop" : 632, "state" : "MA" },<br>
>{ "_id" : "01257", "city" : "SHEFFIELD", "loc" : [ -73.361091, 42.100102 ], "pop" : 1839, "state" : "MA" },<br>
>{ "_id" : "01258", "city" : "SOUTH EGREMONT", "loc" : [ -73.456575, 42.101153 ], "pop" : 135, "state" : "MA" },<br>
>{ "_id" : "01259", "city" : "SOUTHFIELD", "loc" : [ -73.26093299999999, 42.078014 ], "pop" : 622, "state" : "MA" },<br>
>{ "_id" : "01262", "city" : "STOCKBRIDGE", "loc" : [ -73.32226300000001, 42.30104 ], "pop" : 2200, "state" : "MA" },<br>
>{ "_id" : "01266", "city" : "WEST STOCKBRIDGE", "loc" : [ -73.38251, 42.334752 ], "pop" : 1173, "state" : "MA" },<br>
>{ "_id" : "01267", "city" : "WILLIAMSTOWN", "loc" : [ -73.20363999999999, 42.708883 ], "pop" : 8220, "state" : "MA" },<br>
>{ "_id" : "01270", "city" : "WINDSOR", "loc" : [ -73.04661, 42.509494 ], "pop" : 770, "state" : "MA" },<br>
>{ "_id" : "01301", "city" : "LEYDEN", "loc" : [ -72.60184700000001, 42.601222 ], "pop" : 18968, "state" : "MA" },<br>
>{ "_id" : "01330", "city" : "ASHFIELD", "loc" : [ -72.810998, 42.523207 ], "pop" : 1535, "state" : "MA" },<br>
>{ "_id" : "01331", "city" : "NEW SALEM", "loc" : [ -72.21464400000001, 42.592065 ], "pop" : 14077, "state" : "MA" },<br>
>{ "_id" : "01337", "city" : "LEYDEN", "loc" : [ -72.563439, 42.683784 ], "pop" : 2426, "state" : "MA" },<br>
>{ "_id" : "01338", "city" : "BUCKLAND", "loc" : [ -72.764124, 42.615174 ], "pop" : 16, "state" : "MA" },<br>
>{ "_id" : "01339", "city" : "HAWLEY", "loc" : [ -72.880162, 42.621802 ], "pop" : 1325, "state" : "MA" },<br>
>{ "_id" : "01340", "city" : "COLRAIN", "loc" : [ -72.726508, 42.67905 ], "pop" : 2050, "state" : "MA" },<br>
>{ "_id" : "01341", "city" : "CONWAY", "loc" : [ -72.702473, 42.513832 ], "pop" : 1524, "state" : "MA" },<br>
>{ "_id" : "01342", "city" : "DEERFIELD", "loc" : [ -72.60723400000001, 42.540636 ], "pop" : 1281, "state" : "MA" },<br>
>{ "_id" : "01344", "city" : "ERVING", "loc" : [ -72.41663800000001, 42.604957 ], "pop" : 635, "state" : "MA" },<br>
>{ "_id" : "01346", "city" : "HEATH", "loc" : [ -72.839101, 42.685347 ], "pop" : 174, "state" : "MA" },<br>
>{ "_id" : "01349", "city" : "MILLERS FALLS", "loc" : [ -72.494626, 42.576206 ], "pop" : 1893, "state" : "MA" },<br>
>{ "_id" : "01350", "city" : "MONROE", "loc" : [ -72.960156, 42.723885 ], "pop" : 97, "state" : "MA" },<br>
>{ "_id" : "01351", "city" : "MONTAGUE", "loc" : [ -72.532837, 42.542864 ], "pop" : 1699, "state" : "MA" },<br>
>{ "_id" : "01355", "city" : "NEW SALEM", "loc" : [ -72.306241, 42.514643 ], "pop" : 456, "state" : "MA" },<br>
>]);*<br><br>
>#### Output will return document like this
https://simformsolutionspvtltd-my.sharepoint.com/:i:/r/personal/dhruvi_p_simformsolutions_com/Documents/Mongodb_Assignment/Screenshot%20from%202023-03-21%2015-20-52.png?csf=1&web=1&e=d8CHcq

https://simformsolutionspvtltd-my.sharepoint.com/:i:/r/personal/dhruvi_p_simformsolutions_com/Documents/Mongodb_Assignment/Screenshot%20from%202023-03-21%2015-21-14.png?csf=1&web=1&e=xVCOa4
>*"insertMany()" that allows you to insert multiple documents into a collection in a single operation.I have inserted of about 100 documents in my collection called datas.
>*Acknowledgement: true - then all the inserted documents are successfully inserted.

### Question 2
>**Batch Update with minimum 100 records in MongoDB (update batch).**<br><br>
>*db.datas.updateMany(<br>
>{state:'MA'},<br>
>[{$set:<br>
>{state:'Guj'}<br>
>}]);*<br><br>
>#### MongoDB will acknowledge this update by returning following document
https://simformsolutionspvtltd-my.sharepoint.com/:i:/r/personal/dhruvi_p_simformsolutions_com/Documents/Mongodb_Assignment/Screenshot%20from%202023-03-21%2015-21-23.png?csf=1&web=1&e=dRe0h1
>* updateMany() updates all matching documents in the collection that match the filter, using the update criteria to apply modifications.
>*In my collection- the documents containing "state:MA" sets the value of state to "Guj" using $set.

### Question 3
>**Perform indexing on particular 3 fields in MongoDB.**<br><br>
>*db.datas.createIndex({city:1});<br>
> db.datas.createIndex({loc:1});<br>
> db.datas.createIndex({pop:1});*<br><br>
>* This command will create three different indexs on three different columns<br>
>* Note that if we describe all indexes in one query, a compound index of all three fields will generated.<br><br>
>*db.datas.createIndex({city:1, loc:1, pop:1});*<br><br>
>* We can see all indexes on document by this query<br><br>
>*db.datas.createIndex()*<br><br>
>#### Output of above query will be
https://simformsolutionspvtltd-my.sharepoint.com/:i:/r/personal/dhruvi_p_simformsolutions_com/Documents/Mongodb_Assignment/Screenshot%20from%202023-03-21%2015-23-18.png?csf=1&web=1&e=0epdlz

### Ouestion 4
>**Find duplicates using aggregation in MongoDB**<br><br>
>*db.datas.aggregate([<br>
>{'$group:{'_id':'$city','count:{'$sum':1}}},<br>
>{'$match':{'count':{'$gt':1}}},<br>
>{'$project':{'duplicates':'$_id','_id':0}}]);*<br>
>*The $group stage groups documents by a specified key and performs some kind of aggregation operation on the grouped data, such as summing or averaging values.
>*The $match stage filters the documents in the pipeline based on a specified condition.
>*The $project stage reshapes documents in the pipeline by selecting a subset of fields, renaming fields, or creating new fields.
>*1.group by city which concludes to grouping and using $sum we get counts of same documents
>*2.match then filters the documents ,that if count is greater than 1 it gets matched.
>*3.projects the duplicates and shows the output of the query.

>#### Output of above query will be
https://simformsolutionspvtltd-my.sharepoint.com/:i:/r/personal/dhruvi_p_simformsolutions_com/Documents/Mongodb_Assignment/Screenshot%20from%202023-03-21%2015-29-12.png?csf=1&web=1&e=9Qm9X6
