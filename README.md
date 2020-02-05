# DLAD-hw1

I found some starter code to create a basic hello world alexa skill (https://www.hackster.io/auctoris/simple-python-hello-world-with-alexa-4308e4). Most of their code is unused except the json builder to send the response.
![]()

The chatbot is extremely simple and just responds with what you said...with a twist. The text it returns is in alternating case, which gives it this mocking tone (as seen originally in the "mocking spongebob meme")
How to reproduce:
1. Create new lambda function in AWS lambda.
2. Create new Alexa skill.
3. Upload JSON to Alexa skill.
4. Note the Skill ID of your Alexa skill.
5. Upload (copy and paste if needed) lambda_function.py to AWS lambda.
6. Add ASK as a trigger in lambda.
7. Put the noted Skill ID into the field.
8. Note the ARN of the lambda function.
9. Add the ARN as default endpoint in Alexa endpoints.
10. Done.

