Steps to perform a release
------------------------------
1. Modify the release_date_candidate.properties file and change the RELEASE_DT_CANDIDATE to the next release date.

2. Modify the general release notes for PDTool and PDToolStudio
	a. Modify PDTool_releaes_notes.txt
		i. Provide the candidate release date and itemize what has changed for the release.
		
			=========================
			Release Date: yyyy-MM-dd
			=========================
		
	
	b. Modify PDToolStudio_release_notes.txt
		i. Provide the candidate release date and itemize what has changed for the release.
		
			=========================
			Release Date: yyyy-MM-dd
			=========================

3. Build the 6.2 release
	a. All code should be complete and files saved
	b. Right-click on build_release6.2.xml and select "Run As" --> "Ant Build"

4. Build the 7.0 release 
	a. All code should be complete and files saved
	b. Right-click on build_release7.0.0.xml and select "Run As" --> "Ant Build"
	
5. Build the regression release 
	a. All code should be complete and files saved
	b. Right-click on build_regression.xml and select "Run As" --> "Ant Build"
