# csc8017-coursework-2-solved
**TO GET THIS SOLUTION VISIT:** [CSC8017 Coursework 2 Solved](https://www.ankitcodinghub.com/product/csc8017-database-systems-coursework-2-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;131925&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;0&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;0&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;0\/5 - (0 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CSC8017  Coursework 2 Solved&quot;,&quot;width&quot;:&quot;0&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 0px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            <span class="kksr-muted">Rate this product</span>
    </div>
    </div>
This piece of coursework is worth 50% of the total assessment for this module. You are expected to make use of MySQL to complete this coursework. Submit a single answer document to NESS containing your answers to this coursework. NESS will accept .doc/.docx and .pdf files.

Aims:

To assess your ability to:

• Construct SQL queries over a database implementation.

• Decide whether a table is in the first three normal forms or not.

• Decide on an appropriate database architecture to solve given problem statements.

Learning Outcomes:

• To be able to formulate SQL queries.

• To be able to normalise a database table.

• To be able to analyse problem statements and determine an appropriate database architecture.

Problem statement:

You are the manager at a city centre bus station and are wanting to store information about the companies, vehicles and routes that use it.

The bus station has six stands, five in regular use plus a spare in case of a problem. All stands are identified by a unique letter. There are limits on the length of bus that can go on each stand. Note that a bus of the maximum length can fit on the stand, for example if the maximum length permitted on a stand is 10, a 10M long bus can fit on it (but an 11M one can’t).

Routes have a destination and a frequency, expressed as an integer number of buses per hour. Each route uses only one stand in the bus station. For simplicity, the destination is free text (i.e. a VARCHAR). There is no need to store information about all the different places that a route passes through between the bus station and the destination. There is also a Yes/No box (which for simplicity is also a VARCHAR length 3 to accommodate the words “Yes” or “No”) to indicate if a route is suitable for an electric vehicle (EV). Most routes are too long and/or have no charging facilities at the other end for the time being.

A route can be operated by one or more operators. Some basic contact details need to be stored about these operators.

There are a variety of different types of bus which use the bus station. These have a length and a description. Again, this description is free text, though it will always identify if a bus is electric. We also assume that the type of the bus is unique and are not interested in further vehicle details.

Some CREATE TABLE statements have been written. However, the database has not been implemented yet.

There are two linking tables needed for many-many relationships. A route can have multiple operators (with each operator working a proportion of the route). Different operators can operate the same type of bus as well.

The relationship between Route and Stand can be 1-Many because we assume that each route will only ever depart from one stand at the bus station, hence there is a foreign key to represent this relationship.

Tasks:

i) Run all of the CREATE TABLE statements from Appendix A on MySQL to get your database established. You MUST NOT change any of the table structures, data types or keys. Populate your database with the data in Appendix B.

iii) At the moment, the destination of each route is simply a column in the BusRoute table. You have realised that this is not a very good way of storing the destination and raise this with your manager.

Your manager agrees and says that it would perhaps be better to list all stops that a particular route serves, not just the destination. A stop has a unique ID (e.g. 1838201) and a human-readable name (e.g. “Darlington Tubwell Row”). The manager proposes adding all of this into the same table and getting rid of the “Destination” column. The BusRoute table would therefore be:

BusRoute: (number (PK), IDsOfStopsServed, NamesOfStopsServed, frequency, stand (FK), EV).

Where PK and FK are Primary and Foreign Key respectively.

Explain the following in your answer document – you do not need to implement the changes in MySQL:

a) State ONE problem you can think of with having the destination as it is now, a simple column in BusRoute.

b) How many of the three normal form rules would the manager’s suggested change break and why?

c) Think about how you can include the new data without breaking any of the normal form rules. Complete the description of the BusRoute table below and if you feel you would need any new tables, also describe them in the same format. Remember to use (FK) to indicate any columns which are foreign keys. It is up to you how many (if any) new tables you create.

BusRoute: (number (PK),

NewTable: (column 1 (PK), &lt;&lt;as many new columns as needed&gt;&gt;).

iv) One of your friends works for one of the bus companies and has just heard about key-value stores, document databases and graph databases. Your friend is wondering if they should convert their existing relational databases to a graph database or to a document database or to a key-value store or leave it as a relational database. For each of the two databases below, state which one of the databases you would use and give TWO reasons as to why.

a) A database of bus drivers’ personal details including their bank account details to ensure they are paid correctly. There are approx. 500 drivers. The main operations required are to add or delete a driver from the database or to view a driver’s details. b) A database of bus parts. There are approx. 1 million parts. The main operations required are to add or delete parts, view a part’s details and to search for a specific part.

What to submit: A single Word or PDF document containing your answers to the above tasks. You should submit your work electronically through NESS.

This is the end of the assignment but there are two appendices on the following pages that contain the CREATE TABLE statements and the data that you need.

Appendix A

This appendix contains the CREATE TABLE statements needed to get the above scenario working. You should hopefully be able to paste straight into MySQL or DBeaver.

Please do NOT change the table names, column names or any of the keys. You should also not add in any additional tables to those shown here.

These are the basic tables needed for the strong entities. The foreign key in BusRoute is there to stop someone trying to enter a stand that doesn’t exist in the bus station.

CREATE TABLE Stand (ID VARCHAR(1), maxLength INT, PRIMARY KEY

(ID));

CREATE TABLE BusOperator (name VARCHAR(50), address

VARCHAR(100), email VARCHAR(50), phone VARCHAR(15), PRIMARY KEY

(name));

CREATE TABLE BusRoute (number VARCHAR(3), destination VARCHAR(50), frequency INT, stand VARCHAR(1), EV VARCHAR(3),

PRIMARY KEY (number), FOREIGN KEY (stand) REFERENCES Stand

(ID));

CREATE TABLE Bus (type VARCHAR(30), length INT, description

VARCHAR(50), PRIMARY KEY (type));

These are the linking tables needed for the two many-to-many relationships.

Link table OperatesRoute needed for the relationship from operator to route – in this coursework, the proportion will be either 100 if an operator works a route on its own or 50 if it is shared equally with another operator:

CREATE TABLE OperatesRoute (routeNumber VARCHAR(3), operatorName VARCHAR(50), proportion INT, PRIMARY KEY (routeNumber,operatorName), FOREIGN KEY (routeNumber) REFERENCES BusRoute (number), FOREIGN KEY (operatorName)

REFERENCES BusOperator (name));

Link table Uses needed for the relationship from bus operator to bus:

CREATE TABLE Uses (operatorName VARCHAR(50), busType VARCHAR(30), PRIMARY KEY (operatorName,busType), FOREIGN KEY (operatorName) REFERENCES BusOperator (name), FOREIGN KEY

(busType) REFERENCES Bus (type));

Appendix B Stands:

Stand A – max bus length permitted 10M.

Stand F – max bus length permitted 11M.

Stands B, C, D and E – all permit a max bus length of 12M.

Bus Routes:

Route 21: Destination Durham, 2 per hour operated by Northern. Uses Stand B.

Route 54: Destination Gateshead, 4 per hour operated by Northern. Uses Stand F.

Route 308: Destination Blyth, 2 per hour operated equally by Coastline and Northumbria. Uses Stand C.

Route 355: Destination Whitley Bay, 2 per hour operated by Northumbria. Uses Stand C.

Route 366: Destination Cramlington, 1 per hour operated by Moor-Dale Coaches. Uses Stand F.

Route 505: Destination Berwick, 1 per hour operated by Northumbria. Uses Stand D.

Route 518: Destination Alnwick, 1 per hour operated by Northumbria. Uses Stand D.

Route 602: Destination Hexham, 2 per hour operated by Northumbria. Uses Stand A.

Route 722: Destination Darlington, 2 per hour operated equally by Northern and United. Uses Stand B.

Route Q1: Destination Quayside, 2 per hour operated by Northern Uses Stand C.

Only routes 54 and Q1 are currently suitable for electric vehicles. All the others are not.

Bus operators:

Coastline, Coastline House, North Shields, NE29 2AB, e-mail: info@coastlinebuses.co.uk, phone 0191 222 1451.

Moor-Dale Coaches, Dudley Road, Newcastle, NE23 2MD, e-mail moor-dale@gmail.com, phone 0191 255 3272.

Northern Transport Co, The Depot, Chester-le-Street, Co Durham, DH3 1ZZ, e-mail passengerservices@northerntransport.com, phone 0191 300 3000.

Northumbria Motor Services, Jesmond Garage, Newcastle, NE2 2EN, e-mail enquiries@nms.co.uk, phone 0191 208 4929.

United Services, Grange Road, Darlington, Co Durham, DL1 1DK, e-mail customerservices@unitedbus.co.uk, phone 01325 222 555.

Buses:

Olympian, double-deck bus, 10M long. Used by Coastline, Northern, Northumbria and United.

Spectra, double-deck bus, 10M long. Used by Northern.

Tiger, coach, 12M long. Used by Northumbria.

Dart, medium single-deck bus, 9M long. Used by Moor-Dale Coaches.

Delta, single-deck bus, 12M long. Used by Northumbria and United.

Excel, single-deck bus, 11M long. Used by Northern.

Metro, short single-deck bus, 6M long. Used by Northumbria.

Renown, single-deck bus, 11M long. Used by Northern and Northumbria.

E10, electric single-deck bus, 10M long. Used by Northern.

IE, electric single-deck bus, 12M long. Used by Northern.

END OF DATA
