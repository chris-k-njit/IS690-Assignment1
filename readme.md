# IS690 - Assignment 1 
## RestAPI for Creating QR Codes

For this assignment I want you to go over the videos and I've created a X number of errors in the code that you will have to find and fix them.  You should keep running the tests and read the error and try to understand what it mean.  The purpose of this assignment is to get you accustomed to running the project and following the steps that the program uses to process requests.

**To submit this assignment, you should make your own repository and add the remote to git and then push your fixed code to your own repo.** 

### Grading
You will only get 100 if the entire QR program passes GitHub actions, so you will need to update the production.yml file to have your info and setup your environment variables on the repository.

### Installation Guide
1. Clone
2. Make virtual environment:  python3 -m venv venv
3. Activate virtual environment: source venv/bin/activate
4. Install requirements: pip install -r requirements.txt
5. **IMPORTANT** run: mkdir qr_codes to create a qr codes directory to save in, permissions will be messed up and the docker container won't be able to write to the qr_codes directory if you don't.
6. Note: make sure docker is started
7. run pytest locally to check that it works locally
8. Start the app with docker compose up --build
9. Goto http://localhost/docs to view openapi spec documentation
10. Click "authorize" input username: admin password: secret
11. Test making,  retrieving, and deleting QR codes on the spec page.

### Screenshot(s)
![Image in ck378 Docker Hub account](/images/image.png)