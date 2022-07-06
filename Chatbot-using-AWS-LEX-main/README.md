# Chatbot-using-AWS-LEX
To create a chatbot using AWS LEX



                                                                 Introduction


Amazon Lex is a service for building conversational voice and text chatbot into any application. The project aims to helps the user to book pizza, the chatbot can be embedded in any website using a simple javascript snippet.
This is the project about chatbot where users can book pizza. It starts the booking process when a specific input is given. The chatbot then asks multiple questions regarding the pizza booking such as name of the pizza, type of the pizza, date and time. At the end, the bot gives the summary of the order.



AWS Services Used: Amazon Lex


Design steps- Amazon Lex




![IMG 1](https://user-images.githubusercontent.com/63591914/165587591-92873ff9-e6aa-4ec5-a8ef-a0fd10166d74.png)

step-1:open amazon lex and click on create a new bot.



![IMG 2 (2)](https://user-images.githubusercontent.com/63591914/165588029-6949da34-26d7-4d43-818e-356b62b1f92f.png)

Step-2: provide a bot name and choose the language as "English" and choose the IAM role. Bot name is an important entity.




![IMG 3 (2)](https://user-images.githubusercontent.com/63591914/165588519-9e221626-b10b-45bd-9130-44c17682fef8.png)

Step-3: Add the slots to the bot. Slot is a list of pre-defined data types for chat bots. The type of pizza(ex.Italian).



![IMG 4 (2)](https://user-images.githubusercontent.com/63591914/165588981-732a0aba-9607-47d9-bab3-d169c7889947.png)

Step-4: Added the slots like appetizers, pizza crust, pizza type and attatched the slot types to intent list.
The chat bot requires several details like: 
1. Sample utterances: A string to trigger the chat bot pizza booking process(ex: I would like to order {pizzatype} pizza).




![IMG 6 (2)](https://user-images.githubusercontent.com/63591914/165590785-fab189aa-1c84-445b-b2d4-e2d76cbfae71.png)

Step-5: Wrote few sample utterances with the help of slot types.




![IMG 7 (2)](https://user-images.githubusercontent.com/63591914/165591117-8b31adb4-9258-409d-b043-5a8ea3bbad9c.png)

Saved the intent and tested the chatbot, It asks for the name of user and greets the users.



![IMG 8 (2)](https://user-images.githubusercontent.com/63591914/165591369-3abaa05f-15b8-468c-8531-77c9b26997f0.png)

When the user gives the input of pizza type and other features, the chatbot responds by asking the preferred time of delivery. Here, used the button feature for the time function.



![IMG 9](https://user-images.githubusercontent.com/63591914/165591790-3ca4e3eb-effe-4659-8226-d4dde6ab3575.png)

After choosing the time the chatbot gives the summary of the order. 
