# Student-Enrollment-Form

## Description
Student Enrollment Form that will store data in STUDENT-TABLE relation of SCHOOL-DB database. There are three control buttons [Save], [Update] and [Reset] at the bottom of the form. On page load or any control button click, an empty form will be displayed and the cursor will remain at the first input field in the form which will have the primary key(Roll-No) in the relation. All other fields and buttons will be disabled at this time.

<img width="1439" alt="S1" src="https://user-images.githubusercontent.com/120474388/236204101-b42fda7b-5aaf-452f-b98e-ffdb5168f452.png">

User will enter data in the field having primary key and

If the primary key value does NOT exist in the database, [Save] and [Reset] buttons get enabled and the cursor is moved to the next field and the user is allowed to enter data in the form.

<img width="1440" alt="S3" src="https://user-images.githubusercontent.com/120474388/236207952-fcf1130a-8fbc-4919-a727-93e25cc31e30.png">

The form checks that the data is valid i.e. no empty fields.

<img width="1440" alt="S4" src="https://user-images.githubusercontent.com/120474388/236209007-3b60be0f-6a94-46cd-bdc0-d4621e0ab7b8.png">

The user completes the data entry form and clicks the [Save] button to store the data in the database and then the form resets itself.

If the primary key value is present in the database, that data is displayed in the form. [Update] and [Reset] buttons are enabled and the cursor is moved to the next' field in the form. The primary key field is kept disabled and users are allowed to change other form fields.

<img width="1440" alt="S2" src="https://user-images.githubusercontent.com/120474388/236207319-d56ddb0c-ed08-4c01-99f2-82b8b9ff40dd.png">


The form checks that the data is valid i.e. no empty fields.

The user can click on [Update] button to update the data in the database and the form gets reset.

The user can click [Reset] to reset the form.


## Benefits of using JsonPowerDB
JsonPowerDB is a high-performance, NoSQL-based, multi-mode database management system that offers numerous benefits to its users. Some of the key benefits of using JsonPowerDB are:

**Simple and Easy-to-use:** JsonPowerDB is a lightweight and easy-to-use database management system that requires minimal coding and setup. Its simple architecture allows developers to quickly develop and deploy applications.

**High Performance:** JsonPowerDB offers high performance with low latency and high throughput. Its patented indexing algorithm provides faster search and retrieval of data.

**Multi-Mode:** JsonPowerDB supports multiple data models, including key-value, document, graph, and time-series. This allows developers to work with different types of data and easily switch between modes as needed.

**Real-time Data Processing:** JsonPowerDB supports real-time data processing, which means that data can be processed as soon as it is received, without any delays.

**Automatic Data Replication:** JsonPowerDB automatically replicates data across multiple nodes, ensuring high availability and fault tolerance.

**Built-in APIs:** JsonPowerDB comes with built-in APIs for Java, Python, Node.js, and .NET, which makes it easy to integrate with existing applications.

**Cost-effective:** JsonPowerDB is a cost-effective solution as it requires minimal hardware resources and is easy to scale as the data size grows.

In summary, JsonPowerDB is a simple, high-performance, multi-mode database management system that offers real-time data processing, automatic data replication, and built-in APIs. Its cost-effectiveness and ease of use make it an ideal choice for developers looking to develop and deploy applications quickly and efficiently.


## Release History
- 0.0.1
