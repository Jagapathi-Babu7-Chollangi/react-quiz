# Building React-Quiz-App Using Amazon Amplify, Cognito and GitHub CI/CD pipelines

https://github.com/user-attachments/assets/20deab23-1b5d-48dd-843d-70bb37121c17

# Amplify
Amplify is a solution for building and deploying front-end and mobile applications which are 
secure and scalable full-stack applications by AWS. can connect new environments by 
connecting branches from Git and perform CI/CD pipelines.

➢ Used for Server-side Web applications 

➢ Single page Web apps / Static Websites 

➢ Build native mobile applications 

➢ Cross-platform applications 

# Cognito
Amazon Cognito is used for adding user sign-up, sign-in, access control to your web and 
mobile applications with few minutes.  
This verification process serves several important purposes: 

• It confirms that you have access to the email or phone number you provided.

• It helps prevent unauthorized account creation. 

• It adds a layer of security to the sign-up process.


# 1)  install Amplify command line interface(cli) at your local host
![use the commands according to install amplify cli at your l;ocal machine](https://github.com/user-attachments/assets/79383f76-3bb9-4a34-ade5-182444221ff3)
 
# 2) Configuring Amplify it will redirect to amazon console sign-in with IAM user rather than Root user
![2 signin with IAM ACCOUNT](https://github.com/user-attachments/assets/e5f703a9-64db-4513-bc16-75009e96f935)

# 3) To obtain the necessary AccesskeyId and SecretAccessKey, please follow the CLI setup instructions provided in the official documentation.

![2 5 follow cli instructions by documentation to get access key and secret key](https://github.com/user-attachments/assets/a171ffeb-9f5c-4db1-ad24-e496c6d39b9e)

# 4) Create app name of npx create-react-app <name of your app>  here my app is quiz 

![4](https://github.com/user-attachments/assets/59d55941-97b9-4824-9319-cbbac96052aa)

Need to change directory location of your path location cd <name of your app> Cd quiz 

# 5) Initialize amplify amplify init 

![5](https://github.com/user-attachments/assets/3bbc5daf-2d28-431b-808b-41617fad7f1a)

# 6)  amplify add auth and amplify push choose default configuration
![6 update files to gthub](https://github.com/user-attachments/assets/e8539d37-f876-4b04-a40d-d1c14f0e0edc)

npm install aws-amplify @aws-amplify/ui-react these commands provides services and 
enable to react with React app and User Interface of your app(Login Page)

# 7) Run npm start to launch react app at your localhost Create Account with working email account as it will send a Verification code to your email and sign in To open quiz-app  
![npm start to open the user interface and create account using real working email](https://github.com/user-attachments/assets/b86ffc6a-3bdc-44cf-a998-643ce0c26aff)




