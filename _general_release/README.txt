# (c) 2017 TIBCO Software Inc. All rights reserved.
# 
# Except as specified below, this software is licensed pursuant to the Eclipse Public License v. 1.0.
# The details can be found in the file LICENSE.
# 
# The following proprietary files are included as a convenience, and may not be used except pursuant
# to valid license to Composite Information Server or TIBCO® Data Virtualization Server:
# csadmin-XXXX.jar, csarchive-XXXX.jar, csbase-XXXX.jar, csclient-XXXX.jar, cscommon-XXXX.jar,
# csext-XXXX.jar, csjdbc-XXXX.jar, csserverutil-XXXX.jar, csserver-XXXX.jar, cswebapi-XXXX.jar,
# and customproc-XXXX.jar (where -XXXX is an optional version number).  Any included third party files
# are licensed under the terms contained in their own accompanying LICENSE files, generally named .LICENSE.txt.
# 
# This software is licensed AS-IS. Support for this software is not covered by standard maintenance agreements with TIBCO.
# If you would like to obtain assistance with this software, such assistance may be obtained through a separate paid consulting
# agreement with TIBCO.

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
