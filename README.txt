-------------------------------------------Project setup -----------------------------------------------


1. npx create-expo-app AwesomeProject
2. cd AwesomeProject
3. npx expo start


Installation:
npm install @react-navigation/native
npx expo install react-native-screens react-native-safe-area-context
npm install @react-navigation/stack
npx expo install react-native-gesture-handler
npx expo install @react-native-masked-view/masked-view
npm install @react-navigation/bottom-tabs


---------------------------------------- Phone login with Twilio ---------------------------------------

In project installation:
1. npm i react-native-phone-number-input


Twilio website setup:
**Documentation:  https://www.twilio.com/en-us/blog/phone-verification-react-native

1. Go to Twilio.com
2. Create account
3. Go to :  https://console.twilio.com/us1/develop/verify/services
4. Create a new Verify Service. This is what will allow you to send SMS verification messages. Please keep note of SID ( it will help to deploy our twilio application )
5. Now, head over to Twilio's Code Exchange and deploy the One Time Passcode (OTP) verification project => https://www.twilio.com/code-exchange/one-time-passcode-verification-otp
6. 	Step 1:Log in to Twilio
	Account Name : My first Twilio account
	Step 2:Set up your application : *Verify service sid ( SID while created Service )
	Step 3:Deploy your application
	Step 4: Keep note of deployed twilio application URL

