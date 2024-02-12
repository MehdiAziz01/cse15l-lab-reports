# _Part 1_
 ![image](oneline)   ![image](twolines)  ![image](Labreport2code)
#### The methods that are called in my code:
`public static void main(String[] args)` and `public String handleRequest(URI url)` are both being called and the `start` method gets used as well but that implementation is all already given in `Server.java` so I will not use that as a method that I came up with.
#### Arguments to those above methods and relevant fields I used and how do values change from request
For the argument I have them written above, the `URI url` and for `args` i used my port number which is `3875` when I ran my code. for my fields I have a `String` called `OldMessage` which is a blank string and throughout my code it keeps saving my previous messages as my code ran, so I can have the data stored somewhere. I have  `UserParameter` which splits the url into 3 parts and my `Person` field accesses it and gives me the last part which will be behind the colon. In my case it is `Mehdi` and `class`. I have `Message` which splits the already split string again this time by the `&` sign and accesses the 0 element which is the message. In my case that is `Keep being awesome` and `You are an awesome tutor! :D`. Then I have a new field which is called `NewMessage` and this puts it all together with the colon. Then I set `OldMessage` equal to the previous `OldMessage` with the `NewMessage` that was written. I then return `OldMessage`. As for the values changing my `OldMessage` fields's value was the only one that was changing.
# _Part 2_
### `Public Key:`  ![image](Lab2PublicKey)
### `Private Key:` ![image](Lab2PrivateKey)
### `No login proof:` ![image](Lab2NoLogin)


# _Part 3_ 
I learned so many things and about all of it I didn't know. I learned about URl's and how we can alter urls using code. And how our code can change things about url which gets affected on a website. I learned many small things about github including different ways to put images. I also learned how everyone has a specific account they can log into through the terminal and I thought this was really cool!!
