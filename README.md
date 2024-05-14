# Tech Assignment
 # Run Postman collection manually 
  ## Prerequisites: 
1. Postman Installed: Ensure that you have Postman installed on your machine. You can download it from Postman's official website.
2. Clone the project into the local desktop

## Steps for setup the Postman Collection
1. Open the postman 
2. Click on import button in the top left corner 
3. Click on Choose Files and navigate to the location where your collection file (my-collection.json) is saved.
4. Select the file and click Open.
5. Your collection should now appear in the Collections tab on the left sidebar.

## Run the Collection
1. Go to the Collections tab on the left sidebar.
2. on your collection to expand it and see the list of requests.
3. To run the entire collection:
 - Click the Run button (looks like a play button) next to the collection name.
 - The Collection Runner window will open.
 - Make sure all the APis are selected
4. Click the Start Run button.

## Check the Results
 - For collection runs, the Collection Runner will display the results of each request after the run completes. You can click on each request to view detailed results.



# Run Api Cases with Newman and Get the HTML report
 ## Steps to Run API collection via newman: 
 1. Open the NewmanRun Folder in Vs code 
 2. Hit the npm install command to install all the required dependencies
 3. Once all dependencies are installed then Hit newman command to run the collection. 
 4. newman run api_automation.json -r htmlextra --reporter-htmlextra-export 
    ./results/report.html
 4. It will create a report folder and generate the HTML report 

## HTML Report 
 1. Navigate NewmanRun > results folder you will find the already generated HTML 
    report with pass and fail scenarios
[text](NewmanRun/results/report.html)

# Mobile App and API Test Cases and bug document
 1. Open QA_Task_Sheet and you will find three different sheetss 
  - Sheet 1 - Mobile Test Cases - it contains all the Test cases related to Mobile 
    application 
  - Sheet 2 - Api Test Cases - It contains all the Test cases written for 
    Apis which used in automation
  - Sheet 3 - APi Bugs - It contains all the bugs found during the manual 
    and automation execution. 