# kadaHive __PlayTech__

[kada hive logo](images/web/icon.png)

## purpose  software

*parent track their children performes in kada hub*
- show that show the child learning progress

- what have child have learned

- what to learn next

- emailling

- message 

- notifications



## ____message structure

*message KADAHIVE directly*

# simple ajax chat app


*___notification*

 Notify a particular kada user or notify group of kada user by selection feature


## __what kada official can do?
- next Event
- important message
- rate user performerce
- post completed courses
- post child certificate


# DB Data Structure


## users table structure

(`
users{
name: string
email : string 
password : hashed string filePath
learningProgress :  string
performerce : string
level : int,
image : string 
notification : string (tableName)
messages  : string (tableName),
weeklyAddendance : string (tableName)
bio : string (tableName)
}
`)

## admin table structure
*admin will implement coulums for the user table but with some addition coulums as bellow*
(`
admin{
  name : string
password : hashed string filePath
email : password

}
`)
____________
## admin post to user 
(`
adminPosts{//also send email to the user
  to:userId,
  title:"heading",
  message:"<html>"
  type:/message/notification/importantMessage
image:"url"
postBy :default 'kadaHive',
additionalStyle : "css",

}
`);
# more feature in the file
**good lets kick off**
