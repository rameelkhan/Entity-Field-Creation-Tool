# Entity Field Creation Tool
Entity Field Creation Tool is a Windows application which can be used to create entities and fields on just a click of a button!
<!--For detailed use of the product, watch the video: <a href="https://www.youtube.com" target="_blank">Entity Field Creation Tool | Demonstration</a>-->

# Steps to use:
1. Install the managed solution (available with the most latest [release](https://github.com/rameelkhan/Entity-Field-Creation-Tool/releases)) in your Dynamics CRM instance.
2. Assign the user with either ***"System Administrator"*** Role or ***"EFCT App Access"*** Role (which is along with the managed solution).
3. Activate the product from the Configuration Page of the Solution.
4. Fill up the provided Excel Template - ***"Excel Template - EFCT"*** as per your requirement.\
***Note:***\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;i) Excel File Name can be altered as per user requirement.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;ii) Go through the hints available for some of the columns.\
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;iii) Do not alter the Headers and Sheet Names.
5. Now you are good to use the Entity Field Creation Tool.

# Functionalities not supported:
* Fields of type “Image” cannot be created.
* You can only create Simple fields (No Calculated/Rollup fields).
* Global Option Set can not be used for creating fields of “Option Set” type. *(**Planned for next Release**)*
* User need to take care of the field limit in MS CRM for different types of field, especially for fields of type *"Lookup"*, *"Option Set"*.

### Known Issues:
* App screen is freezed while logging in and creating entity-fields, and continues to be in the same state till the respective process is completed. *(**will be resolved in upcoming releases**)*

### Contact:
* For any bug or new feature, please raise an [issue](https://github.com/rameelkhan/Entity-Field-Creation-Tool/issues) against this repository.
