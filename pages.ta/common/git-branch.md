# git branch

> கிளைகளுடன் வேலை செய்வதற்கான பிரதான கிட் கட்டளை.
> மேலும் விவரத்திற்கு: <https://git-scm.com/docs/git-branch>.

- அனைத்து கிளைகளையும் பட்டியலிடுங்கள் (உள்ளூர் மற்றும் தொலைதூர; தற்போதைய கிளை `*` மூலம் சிறப்பிக்கப்படுகிறது):

`git branch {{[-a|--all]}}`

- எந்தெந்த கிளைகள் தங்கள் வரலாற்றில் குறிப்பிட்ட Git கமிட்டை உள்ளடக்கியிருக்கின்றன என்பதை பட்டியலிடுங்கள்:

`git branch {{[-a|--all]}} --contains {{கமிட்_ஹாஷ்}}`

- தற்போதைய கிளையின் பெயரைக் காட்டு:

`git branch --show-current`

- தற்போதைய கமிட்டின் அடிப்படையில் புதிய கிளையை உருவாக்கவும்:

`git branch {{கிளையின்_பெயர்}}`

- ஒரு குறிப்பிட்ட கமிட்டின் அடிப்படையில் புதிய கிளையை உருவாக்கவும்:

`git branch {{கிளையின்_பெயர்}} {{கமிட்_ஹாஷ்}}`

- ஒரு கிளையின் மறுபெயரிடு (இதை செய்ய அந்த கிளையை செக்கவுட் செய்த்திருக்க கூடாது):

`git branch {{[-m|--move]}} {{பழைய_கிளையின்_பெயர்}} {{புதிய_கிளையின்_பெயர்}}`

- கணினியில் ஒரு கிளையை நீக்கு (இதை செய்ய அந்த கிளையை செக்கவுட் செய்த்திருக்க கூடாது):

`git branch {{[-d|--delete]}} {{கிளையின்_பெயர்}}`

- தொலை களஞ்சியத்தில் ஒரு கிளையை நீக்கு:

`git push {{தொலை_களஞ்சிய_பெயர்}} {{[-d|--delete]}} {{தொலை_கிளையின்_பெயர்}}`
