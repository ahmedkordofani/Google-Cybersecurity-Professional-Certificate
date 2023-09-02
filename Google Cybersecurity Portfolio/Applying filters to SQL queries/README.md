**Project Description:**

Throughout this cybersecurity project, I demonstrated my proficiency in SQL query composition and filtering techniques by using SQL queries to extract, filter, and analyze data from the organization's databases. Here are some examples of how I applied filters to SQL queries to investigate potential security issues effectively:

**Filtering Employee Records:**

Objective: Identify employees whose login attempts may pose a security risk.

_Query to retrieve employees with multiple login failures_
```
SELECT employee_id, first_name, last_name, email
FROM employees
WHERE login_attempts > 3;
```
In this query, I employed the WHERE clause with the > operator to filter employee records based on login attempts greater than 3. This filter helped identify employees with a higher likelihood of being involved in security issues.

**Combining Filters with AND and OR Operators:**

Objective: Investigate login attempts originating from unusual IP addresses and devices.

_Query to find login attempts from unusual IP addresses or devices_
```
SELECT employee_id, log_date, ip_address, device_type
FROM log_in_attempts
WHERE (ip_address NOT LIKE '192.168.%' OR device_type = 'Unknown')
  AND log_date BETWEEN '2023-01-01' AND '2023-06-30';
```
Here, I applied multiple filters using the AND and OR operators. The query retrieves login attempts that meet the conditions: not from the organization's internal IP range (192.168.%) or from an unknown device type and within a specific date range.

**Excluding Records with NOT Operator:**

Objective: Exclude successful login attempts to focus on potential security breaches.

_Query to list failed login attempts excluding successful ones_
```
SELECT employee_id, log_date, status
FROM log_in_attempts
WHERE status NOT LIKE 'Success';
```

By using the NOT LIKE operator, I filtered out successful login attempts, allowing me to concentrate solely on failed attempts, which are often indicative of security issues.

**Filtering with NULL Values:**

Objective: Identify login attempts with missing employee IDs.

_Query to find login attempts with missing employee IDs_
```
SELECT log_id, log_date, ip_address
FROM log_in_attempts
WHERE employee_id IS NULL;
```

This query utilizes the IS NULL filter to isolate login attempts with missing employee IDs, which may suggest unauthorized access or data anomalies.

**Project Impact:**

These examples, along with others, are meticulously documented in my GitHub portfolio, complete with SQL queries, explanations, and accompanying screenshots. This documentation illustrates my ability to effectively apply filters to SQL queries to extract and analyze data, ultimately contributing to a thorough investigation of potential security issues. These skills are crucial in maintaining a secure digital environment for our organization


