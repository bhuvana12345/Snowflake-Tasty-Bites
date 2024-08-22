 Snowflake SQL Project for Tasty Bytes Food Truck Analysis

## Introduction

This repository contains a series of Snowflake SQL scripts designed to perform various tasks related to cost management, transformation, semi-structured data handling, governance, collaboration, and geospatial analysis. The data used in these scripts pertains to "Tasty Bytes," a food truck operating in different regions. These SQL scripts help analyze and optimize various aspects of the business using Snowflake's data warehouse capabilities.

For a detailed guide on getting started with Snowflake and understanding the Tasty Bytes dataset, refer to the official Snowflake documentation: [Tasty Bytes Introduction](https://quickstarts.snowflake.com/guide/tasty_bytes_introduction/index.html?mkt_tok=MjUyLVJGTy0yMjcAAAGVCo5Ebb9jNbtq_UWjF-y26vowcj3tbi3Fl_CW4EH8iJwAxLZINVQl5QDQsyjEfvzbDzmDxH55dLCzBgpRdMcSRxA7kOCmI-jP9MX-NrQE8w9qiirqiw).

## Folder Structure

### 1. Introduction
- Basic SQL queries to get started with Snowflake.

### 2. Cost Management

#### a) Cost Optimization
1. **Virtual Warehouses and Settings**: Optimize the configuration and usage of virtual warehouses.

#### b) Cost Control
2. **Resuming, Suspending, and Scaling a Warehouse**: Manage warehouse operations efficiently.
3. **Setting up Session Timeout Parameters**: Configure session timeouts to control costs.
4. **Setting up Account Timeout Parameters**: Manage account-level timeout settings.
5. **Setting up Resource Monitors**: Monitor and control resource usage.

#### c) Cost Visibility
6. **Tagging Objects to Attribute Spend**: Use tags to track and manage costs.
7. **Exploring Cost with Snowsight**: Analyze costs using Snowsight's visualization tools.

### 3. Transformation
1. **Zero Copy Cloning**: Efficiently clone databases and tables.
2. **Using Persisted Query Results**: Optimize queries using persisted results.
3. **Adding and Updating a Column in a Table**: Modify table structures.
4. **Time-Travel for Table Restore**: Restore tables using Time-Travel.
5. **Table Swap, Drop, and Undrop**: Manage table lifecycle operations.

### 4. Semi-Structured Data
1. **Semi-Structured Data and the Variant Data Type**: Handle semi-structured data using Snowflake's Variant data type.
2. **Querying Semi-Structured Data via Dot and Bracket Notation + Flatten**: Query nested data structures.
3. **Providing Flattened Data to Business Users**: Transform and share flattened data.
4. **Analyzing Processed Semi-Structured Data in Snowsight**: Use Snowsight for deeper analysis.

### 5. Governance with Snowflake Horizon

#### a) Protect Your Data
1. **System Defined Roles and Privileges**: Understand and use system-defined roles.
2. **Role-Based Access Control**: Implement role-based access control (RBAC).
3. **Tag-Based Masking**: Apply masking policies based on tags.
4. **Row-Access Policies**: Manage data access at the row level.
5. **Aggregation Policies**: Control data aggregation and access.
6. **Projection Policies**: Manage data projection rules.

#### b) Know Your Data
7. **Sensitive Data Classification**: Identify and classify sensitive data.
8. **Sensitive Custom Classification**: Define and apply custom classifications.
9. **Access History (Read and Writes)**: Track and audit access to data.

#### c) Discovery with Snowflake Horizon
10. **Universal Search**: Explore data assets using universal search capabilities.

### 6. Collaboration
1. **Investigating Days with Zero Sales**: Analyze sales data for insights.
2. **Acquiring Weather Source Data from the Snowflake Marketplace**: Enhance data with external weather sources.
3. **Democratizing First and Third Party Data**: Share data across the organization.
4. **Using Harmonized Data to Answer Questions from the Business**: Leverage harmonized data for business analysis.

### 7. Geospatial
1. **Acquiring Safegraph POI Data from the Snowflake Marketplace**: Work with geospatial data from Safegraph.
2. **Harmonizing and Promoting First and Third Party Data**: Integrate and promote geospatial data.
3. **Creating Geography Points from Latitude and Longitude**: Generate geographic points for analysis.
4. **Calculating Straight Line Distance between Points**: Measure distances between geographic points.
5. **Collecting Coordinates, Creating a Bounding Polygon & Finding its Center Point**: Perform advanced geospatial operations.
6. **Finding Locations Furthest Away from our Top Selling Hub**: Identify distant locations for analysis.
7. **Geospatial Analysis with H3 (Hexagonal Hierarchical Geospatial Indexing System)**: Conduct geospatial analysis using H3.

---

### Additional Resources
For more details on how to use Snowflake and the Tasty Bytes dataset, please refer to the official Snowflake [guide](https://quickstarts.snowflake.com/guide/tasty_bytes_introduction/index.html?mkt_tok=MjUyLVJGTy0yMjcAAAGVCo5Ebb9jNbtq_UWjF-y26vowcj3tbi3Fl_CW4EH8iJwAxLZINVQl5QDQsyjEfvzbDzmDxH55dLCzBgpRdMcSRxA7kOCmI-jP9MX-NrQE8w9qiirqiw).

