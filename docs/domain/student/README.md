# Student

🚧 TODO 🚧

Attribute | Type | Description
------ | ------ | ------ |
username | text (length=6..20) |  the name of the account
password | text (length=6..20) | the password of the account

Example: Valid Student
---

Attribute | Value |
------ | ------ | 
username |  johnny850807|
password |  850807johnny|


Example: Invalid Student (Length invalid)
---

Attribute | Value | Failure |
------ | ------ | ------ |
username |  johnny | Length < 6 |
password |  123456789012345678901234 | Length > 20 |

