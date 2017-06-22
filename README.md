Group 5

ICS 311
=========
Term Project Step 1

Our application:
----------------
The Guardian Life database will be used to store important client information for a life

insurance company. There is a total of four life insurance sales persons at this small agency so

the database will help them and help the agency track productivity, file progress, and client

information. This system has tables that are broken down to smaller, relevant pieces. This should

help them stay organized as they add in new agents. The Agent table will track who the

recruiting agents are because the agency rewards agents who recruit more. The Productivity table

will track new customers with application dates and Issue dates. Each policy has an owner, an

insured, and a beneficiary or beneficiaries so there are separate tables to track them all.



Productivity Table
------------------
1App DateAgent IDAgent NameCustomer IDCustomer NamePolicy NumberIssue Date

Agents
--------
2Agent IDAgent NameCommission LevelRecruiting Agent ID

Policy Owners
------------
3Customer IDPolicy OwnerStreet AddressCity, State, ZipBirthdayAgeContact_NumberPolicy Number

Insureds
-----------
4Customer IDPolicy NumberInsured NameStreet AddressCity, State, ZipBirthdayAgeContact_Number

Beneficiaries
--------------
5Customer IDPolicy NumberBeneficiary NameStreet AddressCity, State, ZipBirthdayContact_Number
