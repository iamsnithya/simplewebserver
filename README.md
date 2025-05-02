# EX01 Developing a Simple Webserver
## Date: 02/05/2025

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:


    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <title>TCP/IP Protocol Suite</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            padding: 40px;
            text-align: center;
        }
        h1 {
            font-weight: bold;
        }
        table {
            width: 60%;
            border-collapse: collapse;
            margin: 20px auto; /* centers the table */
        }
        th, td {
            border: 3px solid black;
            padding: 5px 8px; /* reduced padding for compactness */
            text-align: center; /* center-align the text inside cells */
            font-size: 16px; /* slightly smaller font if needed */
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
    </head>
    <body>

    <h1>TCP/IP Protocol Suite</h1>

    <table>
        <tr>
            <th>Layer</th>
            <th>Protocols</th>
        </tr>
        <tr>
            <td>Application Layer</td>
            <td>HTTP, HTTPS, FTP, SMTP, DNS, DHCP, Telnet, SNMP</td>
        </tr>
        <tr>
            <td>Transport Layer</td>
            <td>TCP, UDP</td>
        </tr>
        <tr>
            <td>Internet Layer</td>
            <td>IP, ICMP, ARP, IGMP</td>
        </tr>
        <tr>
            <td>Network Access Layer</td>
            <td>Ethernet, Wi-Fi, PPP</td>
        </tr>
    </table>

    </body>
    </html>



## OUTPUT:

Name : NITHYA S

Reg no : 212224240106

![web ex 1](https://github.com/user-attachments/assets/690e1b7c-5e6c-4207-8451-92db1d6a96ba)



## RESULT:
The program for implementing simple webserver is executed successfully.
