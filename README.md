# <div align="center">**PWA Budget Tracker**</div>

## **Project Description**
> Your challenge this week is to update an existing budget tracker application to allow for offline access and functionality. The user will be able to add expenses and deposits to their budget with or without a connection. If the user enters transactions offline, the total should be updated when they're brought back online. Once you’ve made these changes, you’ll deploy the application to Heroku.

## **Table of Contents** 
* [Project Description](#project-description)  
* [Table of Contents](#table-of-contents)  
* [Application Links](#application-links)  
* [Contributors](#contributors)  
* [Development](#development)  
* [User Story](#user-story)  
* [Acceptance Criteria](#acceptance-criteria)  
* [Screenshots](#screenshots)
* [Questions](#questions)  

## **Application Links**
> [Heroku](https://boiling-springs-33052.herokuapp.com/)  
> [GitHub Repository](https://github.com/hadleyc15/pwa-budget-tracker)

## **Contributors** 
> Christopher Hadley | <hadleyc15@yahoo.com> | [github](https://github.com/hadleyc15)    

## **Development**
This application was developed with the following application structures:

1. [Node.js](https://nodejs.org/en/)
2. [Express.js](http://expressjs.com/)
3. [Mongoose](https://mongoosejs.com/)
4. [Morgan](https://www.npmjs.com/package/morgan)
5. [Compression](https://www.npmjs.com/package/compression)
6. [Dotenv](https://www.npmjs.com/package/dotenv)

---

## **User Story**

> AS AN avid traveler
> I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
> SO THAT my account balance is accurate when I am traveling

## **Acceptance Criteria**
> GIVEN a budget tracker without an internet connection
> WHEN the user inputs an expense or deposit
> THEN they will receive a notification that they have added an expense or deposit
> WWHEN the user reestablishes an internet connection
> THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated


## **Screenshots**

### <div align="center">**Budget Tracker Main Screen**</div>
<img src="/assets/images/Screenshot%20(107).png" />

### <div align="center">**Offline transactions added to cache**</div>
<img src="/assets/images/Screenshot%20(108).png" />

### <div align="center">**Cached transactions posted once internet is connected**</div>
<img src="/assets/images/Screenshot%20(109).png" />


## **Questions**
>If you have any questions, please contact me (contact info is listed in the CONTRIBUTORS section of this README).