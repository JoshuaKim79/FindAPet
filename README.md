# FindAPet
> An app birthed during Georgia Tech's 2021 Hackathon that allows app users to potentially identify lost pets.
- Person who lost their pet would submit a form in the app that details their lost pet.
- Details: Name, color, breed, location of last saw, submitted picture (ideal for application of computer vision), behavior (for post picture matching identification), special characteristics, phone number or other forms of contact (important)
- App user would be pinged if they are in the area of pet last saw (optional)
- (Main use case) app user sees a lost looking animal and uses the camera through the app to take a picture (simple) or a video of the pet. Computer vision runs matches with the taken picture to see if there is a match.
- If the match threshold is met (70%?), then the submitted form for the supposed match is pulled up for the user to see if they can match the animal. They can use behavior identifications or special characteristics
- Once done matching, the user can contact the form submitter via 
- Alternatively, if the threshold is met, the form submitter can be pinged via app or contact with the picture/video of the pet and the location as well as the contact of the picture taker (important for picture taker to provide contact).
