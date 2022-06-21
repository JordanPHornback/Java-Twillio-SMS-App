# Java-Twillio-SMS-App

This is a Java SMS app built using the Twilio API (I know, I know, I misspelled Twilio in the repo name).

This was built using Apache Netbeans.

It has been designed so that after downloading the files and inputting your own Twilio Auth Token and Account SID, building the project will give you a
JAR file that includes all required dependencies allowing you to run the application directly from the JAR file.

The purpose of this application is to allow a user to send SMS messages to a list of phone numbers (or just one), like the text blasting that is a 
necessity of so many businesses.

Once you have added your credentials to your local version of this code and created a new build of the project, your executable JAR file will render
an SMS interface that has two fields and a send button. The first field is the recipient field, where you list the phone numbers you would like to text,
and the second is the message field, where you type the message you would like sent to all of the listed phone numbers.

When you hit send, your text message goes out to all listed phone numbers! There is no reset required, simply change your phone numbers or messages and you
can hit send again.
