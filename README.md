# HW4-345

# Submissions:
In this repo, you will find all the things you need for my HW4.
 - Test cases for the GITHUB API can be found in the test_cases.jpg
 - Running the server can be found in the Server_test_video.mp4 , not in a link.
 
# Answers Explanations:
 - listBranches pulls all branches from a specific repo, then loops through and names each one.
 - createRepo POSTs a new repo object to the specific users repo collection. (However, the repo name has to be vacant in order to pass the test case)
 - createIssues takes in a issue name and issue body, then POSTs an issue to a specific repo.
 - enableWikiSupport uses PATCH to grab a specific repo and its attributes, then will change the has_wiki attribute to the passed boolean. In the test's case, to 'true'
