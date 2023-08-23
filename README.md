![image](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/bb83ff33-2dd3-41fd-a8a8-7e2172c1f710)# Ali_Khatami_Etherjs7(Learning from the video of Patrick Collins)

### Environment variables 

Remember if we give out our private key whoever has our private key <br>

owns our fund <br>

We don't want to hard code our private keys into our code <br>

just in case we accidentally we share code with someody <br>

Then the solution of above is creating .env file <br>

or environment variable <br>


![d53](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/2d87449b-cfcb-485e-8046-5d10e0b8c6f4)

we create a .env file that gonna contain sensitive information <br>

This sis gonna bethe file that we never gonna share with anybody <br>

This file gonna stick variables of our choosing to our environment varibales <br>

![d54](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/c9e1765b-1209-4d4d-895d-c993e0ba82e8)

here the below code :

```
$env:HUMAN = "Khatami"
```

```
echo $env:HUMAN
```


This is what an environent variable is <br>

It sis a variable in our terminal or scripting environment <br>

In our akrkdeploy.js we want ot grab the above enironment variable <br>

and stick it to the script at akrkdeploy.js <br>

So that our script can stick it to our environment <br>

![d55](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/71147c7b-234f-4257-be0d-6f2f398abee3)

We gonn paste the code below :

```
yarn add dotenv
```


![d56](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/fe5205df-9d1d-443b-95cc-676c97e38c8f)

We can go to this link  https://www.npmjs.com/package/dotenv <br>
to learn more about dotenv <br>



![d57](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/5c10ef85-2e47-45f1-8b2d-b6b1a4450005)

This pull all our environment variables <br>

![d58](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/314af8a8-f668-428d-a3cf-d5cf78b78dee)

We shall see in our package.json <br>

Now we pulled it in we can get access to our private key variable <br>

![d59](https://github.com/C191068/Ali_Khatami_EtherJs7/assets/89090776/a49d59ce-051f-4e65-a38c-f019e2207ece)

We use the above line of code <br>















