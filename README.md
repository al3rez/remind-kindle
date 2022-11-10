<h1 align="center" style="font-size: 10rem;">
Remind Kindle 
<img src="logo.svg" height="24px" />
</h1>

Get reminder emails of your favorite kindle highlights *without sharing them with others* 📔🔖 with the help of Github Actions.


## Installation

1. Fork/Clone the repo. 
2. Replace `My Clippings.txt` with your own and commit and push the changes.
3. Enable Github Actions.
4. Enable 2-Step Verification on the Gmail account and generate a new app password for mail.
4. Add `SENDER_EMAIL` (preferrablly Gmail) , `SENDER_APP_PASSWORD` , `RECEIVING_EMAIL` and `NO_OF_HIGHLIGHTS` (optional: default is 5) to the repository's secrets. (Refer [.example.env](/.example.env))
5. Done.

## Available Options/Features
- Change the mail frequency from [workflow file](./.github/workflows/main.yml).
- Change number of highlights in the emails from repository's secret.
 
## Email Screenshot
<img width="405" alt="Only 1 highlight" src="https://user-images.githubusercontent.com/73903781/200693278-b84c6d7a-d3e3-4db5-9023-4c0473dc753b.png">

## Contributing

Contributions are always welcome!