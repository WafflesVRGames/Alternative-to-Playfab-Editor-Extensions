# Alternative-to-Playfab-Editor-Extensions
Playfab Editor Extensions is probably going to break when Microsoft fully migrates Playfab accounts to Microsoft accounts, so I made scripts that you can use to add Playfab to your Unity project.
Use UnitySDK or this will not work. https://github.com/PlayFab/UnitySDK

SETUP

Import the PlayfabAuthenticator.unitypackage

Create a Empty GameObject

Add the PlayfabManager script to the empty gameobject

Put your playfab title id in the "Play Fab Title ID" input feild

Go to the Playfab webstite and login

Navigate to Automation → CloudScript → Revisions (Legacy)

Then paste the code from "PUT THIS IN PLAYFAB SCRIPT"

Click Upload new revision then check 
Deploy this revision after save then click Save and deploy

END OF SETUP
