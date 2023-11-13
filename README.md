# Gram AI

Gram AI is a AI bot that can chat with user as a response generator using Google BARD api. Powered by the aiogram library in Python language.

## Google Bard Token

Go to https://bard.google.com/

- F12 for console
- Copy the values
- - Session: Go to Application → Cookies → `__Secure-1PSID` and `__Secure-1PSIDTS`. Copy the value of that cookie.

![Application -> Cookies -> https://bard.google.com/ -> __Secure-1PSID and __Secure-1PSIDTS](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEjB65H-gfluvq_woF3U1rw2cz9KT2oX6UeqeYpMP8UuR9Dt0COt3F-z5KMHvzNGajNdXEec-n3Ej2qu934HLoLx29Td2RbPusiZ_QLNXz85VwusnjTyJNmEMOE2Hh4gbQGxjcGb8pkyFGbNOwdyb9ygPRct7qvazxsuCf7EM6MN2d_zWo1etSAoo2tZPMU/s1600/screen.png)

## Telegram Bot token

Now we need to create a bot in a telegram, this is done through **@BotFather**, start a dialogue and enter the command `/newbot`, select a name, be sure that the name contains the word: `Bot`, or through the underscore `_bot`

![BOT Example](https://blogger.googleusercontent.com/img/b/R29vZ2xl/AVvXsEgemsaBg67lAcJMS7EqAeB2Ee7LGp-EKDX2EkCAFGQ3WIlPZTN_rUCrEcUAmMqOCjEYbkkQnYNnksvyj4sm5C_4cXQrYshoN2QRClMhVoLaR9GREtU8nu8EsjpenbFwxsqMcpkqhkn6btbkullXqkqVr_AbtSEJoR_CUoZqU6dt0F-ar1P1qnUePeaD7Ow/s1600/Screenshot%20from%202023-11-13%2023-02-30.jpg)

We get the key to access **API**, it is shaded in the screenshot.

## Launch Bot

- In vps,
  `git clone https://github.com/ShejanMahamud/GRAM-AI`
  `cd GRAM-AI`
  `pip install -r requirements.txt`
  `python3 main.py`

## Dialog with a bot

![Dialog screenshot 1](https://proghunter.ru/media/images/uploads/2023/05/14/256ffa2248-uploaded-image.png)

![Dialog screenshot 2](https://proghunter.ru/media/images/uploads/2023/05/14/7709de8995-uploaded-image.png)

## Proxy or VPN

Without using a proxy/vpn, you may encounter the following error:

```
Google Bard encountered an error: b')]}\'\n\n38\n["wrb.fr",null,null,null,null,[9]]\n56\n["di",196," af.httprm",196,"5929433453807571131",4]\n25\n["e",4,null,null,131]\n'.
```
