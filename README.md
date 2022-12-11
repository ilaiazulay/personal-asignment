# back-office-phase2-Personal Assignment

## Description
Phase 2 personal assignment - admin and users manager.
There are two roles: user, admin.
User has status: active / disabled, only admin can control this field.
If user disabled he can only view his data.
Only admin can alter data of other users.
A user can alter his data.
Admin can alter several users in a single request
Admin can get a filtered users list by criterias.
There are fields updatedAt and createdAt that update accordingly.


 ## Prequisites
 ```
 Node.js 16v
 ```
## Installing
Install dependancies
```
npm i
npm install express
npm install path
npm install mongoose
npm install dotenv
npm install cors
npm install url
npm install open
```
create .env file with the following variables:
```
DB_HOST=mongodb+srv://ilaiazulay1:ilaiazulay@cluster0.9koarsm.mongodb.net/backOffice?retryWrites=true&w=majority
DB_USER=ilaiazulay1
DB_PASS=ilaiazulay
```
Run the server:
```
npm run dev
```
Open page firstPage.html with live server

## API Docs
**only working calls in the docs**
https://documenter.getpostman.com/view/5840775/2s8YsnVvTk

## Built with
- Node.js
- HTML
- CSS
- JavaScript

## Authors
- ***IlaI Azulay*** (ilaiazulay) - SE student
