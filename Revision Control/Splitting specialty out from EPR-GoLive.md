# Splitting specialty out from EPR-GoLive
## Summary
To create a branch with just the Cardiology files in them:

1.  Save the Cardiology files somewhere
2.  In GitHub Desktop switch to main, then create a new branch
3.  Copy the Cardiology files across
4.  Check-in and publish

Then to publish to staging:

1.  Create a 'Pull Request'
2.  Make sure this is from the Cardiology branch to Staging. By default it is to 'main'
3.  Create, then merge, don't delete the Neonates branch just yet

>> Create a branch with just the Cardiology files in them

### 1. Create a copy of the files to split out
* Check you are on the EPR-GoLive branch
![[1 - EPR-GoLive Branch.png]]
* Copy files to a temporary location

### 2. Switch to main and create a new branch
![[2 - New branch.png]]
![[2-1 Create new branch.png]]

### 3. Copy the files back
![[Cardiology.png]]

### 4. Commit and Publish

![[3 - Commit.png]]![[3-1 Publish.png]]
<<
>> Publish to staging

In GitHub Desktop 'Publish branch' then 'Create Pull Request'

![[3-1 Publish 2.png]]
![[Create Pull Request.png]]

You'll be taken to the GitHub website. Change the destination from 'main' to 'staging', then press ' Create pull request'.
![[Open a pull request.png]]
![[main to staging.png]]

Merge the pull request and a few minutes later the change will be live on https://guidelines.fhft.nhs.uk/staging
![[Merge pull request.png]]
<<