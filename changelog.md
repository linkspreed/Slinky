# V2.4.7 (14 January, 2023)
- Fixed issue that caused upload folders to stay on the webserver when external storage plugin was installed.
- Fixed limit issue on admin user page
- Fixed email recipient list splitting
- Changed some parts of the user authorization process
- Changed droppy log to download button
- Updated translation files

# V2.4.6 (13 October, 2022)
- Added support for uploading folders
- Added authentication support for future add-ons
- Added download expiration time to download page
- Added more options for email list pasting such as spaces " " or semicolons ";"
- Fixed issue that caused the amount of upload expire time options to be limited
- Some general bug fixes and textual changes

# V2.4.5 (17 August, 2022)
- Fixed issue that caused incorrect email error when trailing blanks were added in the email address
- Fixed issue with the background on login page
- Fixed issue that caused about tab to stay visible on mobile when the contents were empty
- Fixed issue that allowed upload button spamming and multiple verify emails to being sent
- Fixed issue that caused uploads with share mode link to still send out emails to uploaders
- Updated translation files based on customer input
- Updated core framework

# V2.4.4 (18 July, 2022)
- Fixed issue with incorrect pointer icon on file previews
- Fixed issue where temp folder wasn't automatically cleared in some setups
- Fixed missing translation for "Preview files" text
- Fixed some dutch translations
- It is now possible to preview download details and view file previews when the upload is password protected

# V2.4.3 (11 July, 2022)
- Fixed issue that caused cron to not work properly when using the S3 add-on
- Fixed issue that caused the user to be redirected to a white page when the download password was incorrect
- Fixed possible download issue with systems that were upgraded from Droppy V1 to V2
- Fixed some issues with IP logging
- Fixed some mobile height issues
- The terms and about tabs will now be hidden when their content is empty
- Added file previews on download page (optional feature)
- Added new directory permission checks to admin panel
- Deprecated: Themes "default", "grey" and "oldtimer" are now deprecated and will no longer be supported. Please use the new "modern" theme.

# V2.4.2.1 (15 May, 2022)
- Quick patch for issue that caused downloads to fail with the old themes

# V2.4.2 (5 May, 2022)
- Fixed an issue that caused the downloading of files not to work in some mobile browsers
- Fixed an issue that caused some incorrect tabs to be shown in the header when using the Premium add-on

# V2.4.1 (17 March, 2022)
- Fixed issue where upload buttons wasn't showing in the latest update of Safari
- Added message to download page when using Facebook in-app browser

# V2.4.0 (21 January, 2022)
- Fixed issue with base URL in custom navbar pages
- Fixed issues with email verification form
- Email verification code form can now be submitted using the enter button
- Added cron job to clean up pending email verifications
- Added "view video" button to video backgrounds on the backgrounds page in the admin panel
- Improved session security

# V2.3.9 (5 January, 2022)
- Added email verification option to verify the sender's email address using a verification code
- The change language tab will now stay hidden when there's only 1 language available
- Language select list is now sorted in alphabetical order
- Site logo is now clickable and points to home page
- Added advertisement space to mobile version

# V2.3.8 (7 November, 2021)
- Added option to add custom pages and tabs
- Added expiration date to admin uploads page
- Added recaptcha to normal user login
- Improved loading of animated icons

# V2.3.7 (2 October, 2021)
- Fixed issue where incorrect file sizes where shown on the download page
- Fixed issue where removing file from upload selection would cause the total to reset to 0
- Fixed tab window size issue on ipad
- Fixed logging issue
- Added extra margin to captcha on contact form
- Updated French and German translation files
- Removed "Powered by Droppy" from admin page

# V2.3.6 (19 September, 2021)
- (Modern theme) Added translation for connection issue popup
- (Modern theme) Added translation for "no expire" option
- (Modern theme) Added option to specify multiple default recipients in "Default recipients" input and added email select dropdown to upload form
- (Modern theme) Added option to hide "Share type" option from upload form
- (Modern theme) Added option to hide "Destruction" option from upload form
- (Modern theme) Added option to specify default expiration time
- (Modern theme) Fixed possible auto-fill issues on password input
- (Modern theme) Fix expiration date being shown on download page when upload expiration is disabled
- Fixed JS error in admin panel
- Fixed destruction email not being sent immediately when the upload is marked as inactive

# V2.3.5 (2 September, 2021)
- Added upload expiration option to upload form
- Added dark mode toggle to admin panel
- Added missing "My account" page to admin panel
- Fixed issue where download link in sender email would not work
- Fixed issue in admin panel where clicking on the logo would not bring you back to the admin home page
- Fixed styling of email settings page in the admin panel
- Fixed infinte reloading issue on system page
- Fixed issue where htaccess message was incorrectly showing
- Moved upload settings to separate page in the admin panel

# V2.3.4 (31 August, 2021)
- Redesigned admin panel
- Added recaptcha to admin panel login
- Added debugging mode
- (Modern theme) Added automatic upload resume on network failure
- (Modern theme) Fixed issue with error message and help message showing at the same time
- (Modern theme) Advanced upload options will now open faster
- (Modern them) Small mobile improvements

# V2.3.3 (21 August, 2021)
- Added changes for upcoming premium add-on update V2.0.10
- Small database performance improvements to upload handler
- Improved session handling
- (Modern theme) Fixed some small styling issues on mobile
- (Modern theme) Fixed some inconsistency issues with the help info popups
- (Modern theme) Fixed issue where user login page wasn't shown properly on mobile
- (Modern theme) Fixed issue with closing tab window on download page
- (Modern theme) Fixed issue where it wasn't possible to switch language on the download page
- (Modern theme) Added extra font smoothing and backup fonts
- (Modern theme) Language selection will now be blocked while uploading
- (Modern theme) Fixed language selection not working on download page
- Fixed issue where upload wouldn't work properly when there were no blocked file types specified
- Redesigned installation page

# V2.3.2 (18 August, 2021)
- Added extra security checks to check if the application/.htaccess file exists.
- (Modern theme) Fixed issue where incorrect download password didn't show error message.
- (Modern theme) Fixed upload form height issues on mobile devices
- (Modern theme) Fixed missing line-breaks in download message and made the message scrollable
- (Modern theme) Fixed upload percentage not always showing immediately
- (Modern theme) Fixed auto-fill issue on email to field
- (Modern theme) Added total files left indicator
- (Modern theme) Added small border to tab window
- Added option to specify the upload ID length
- Added option to auto-fill sender email on next site visit

# V2.3.1 (11 August, 2021)
- Improved uploading of large selection of files (100+)
- Added ability to specify email button color for each theme
- (Modern theme) Added logout buttons to modern theme
- (Modern theme) Added option to specify different theme colors (can be found on the themes page)
- (Modern theme) Fixed text sizing issue on Safari
- (Modern theme) Added help popups to upload option section

# V2.3.0 (5 August, 2021)
- Added option to disable IP logging
- Changes for Premium add-on V2.0.9
- Fixed issue where default email to was not set

# V2.2.9 (5 August, 2021)
- (Modern theme) Fixed issue where background was not clickable
- (Modern theme) Fixed issue where error message popup didn't disappear
- (Modern theme) Fixed issue where upload box corners weren't always round
- (Modern theme) Improved recipient adding process
- (Modern theme) Improved calculation of file sizes and progress size indication
- (Modern theme) Prevent auto-zoom on mobile
- Added extra database connection checks to the installation
- Updated german translation file
- Updated turkish translation file
- Small code improvements

# V2.2.8 (31 July, 2021)
- Fixed issue with background transition not being smooth
- Fixed issue where missing mobile-header.php error was shown V2.2.7 (30 July, 2021)
- Fixed issue in modern theme where contact form was still shown when disabled
- Fixed issue where default share type wasn't working V2.2.6 (30 July, 2021)
- Added a complete new modern theme
- General bug fixes

# V2.2.5 (17 July, 2021)
- Fixed invalid email error message
- Fixed missing asset in installation
- Fixed small issues with plugin pages
- Fixed custom upload directory feature
- Fixed issue where upload password was being autocompleted by the browser
- Fixed issue where download email was being sent when the admin or uploader downloads a file
- Fixed issue where Invalid email error was thrown when the email input field was empty but the recipient list wasn't

# V2.2.4 (22 June, 2021)
- Fixed missing jquery file since update 2.2.3

# V2.2.3 (21 June, 2021)
- Fixed issue where email fields weren't verified
- Fixed issue where "Okay" button was disabled on password protected uploads
- Minor changes for the premium add-on

# V2.2.2 (12 May, 2021)
- Fixed issue with autofill of user email
- Added turkish translation

# V2.2.1 (09 May, 2021)
- Fixed some installation issues
- Updated some libraries for the mobile version

# V2.2.0 (07 May, 2021)
- Updated core framework
- Updated dependencies
- Small code improvements

# V2.1.9 (10 July, 2019)
- Added option to define maximum upload chunk size in the admin panel
- Fixed an issue where downloads were corrupted

# V2.1.8 (10 July, 2019)
- Fixed an issue where upload password field was locked for premium users
- Fixed an issue where the direct open link wouldn't open the right modal on the mobile version
- Fixed an issue with the favicon file not loading on download page.

# V2.1.7 (10 July, 2019)
- Added a delay to the "Okay" button after starting the download
- Fixed an issue where {size} placeholder in emails was showing the incorrect file size
- Fixed an issue where meta keywords weren't included in the mobile version
- Updated the project framework
- Decreased the total project size of Droppy

# V2.1.6 (31 May, 2019)
Added:
- Added validate email address function to contact form 
- Contact form will no longer disappear after sending an email
- The recaptcha in the contact form is now optional (Disable it by leaving the site key and secret key empty in the admin panel)
- Users will be redirect back to the home page when trying to access the /upload page
- Improved zipping speed, this causes a minor increase in file size
Fixed:
- Issue where browser would report errors when leaving the recaptcha site key empty
- Height of plugin views
- Issue with email library in PHP 7.2+
- Issue with automatic updater

# V2.1.5 (7 May, 2019)
Added:
- Added separate translation values for contact input placeholders
Fixed:
- Fixed an issue with incorrect file size in emails when file is larger than 1 GB
- Fixed an issue with links not showing correctly in the success alert.

# V2.1.4 (6 May, 2019)
Added:
- Added contact form (needs to be enabled in the admin panel)
- Added contact form settings to the admin panel
- Added recaptcha settings to the admin panel
- Added new manual update functions
- Added site keywords setting to the general settings page for SEO
- The file size in emails will now be shown as KB, MB or GB depending on the file size (Make sure to update your email templates)
Changed:
- Changed the upload speed from Megabytes per second to Megabits per second (The speed most ISPs will advertise)
- The uploader will now show the total file size and file size left in Gigabytes when the total size is greater than 1000 Megabyte
Fixed:
- Fixed an issue with redirecting after selecting an email template language

# V2.1.3 (29 April, 2019)
Fixed:
- Fixed an issue with redirect after logout in admin panel
- Fixed an issue that caused loading the wrong admin url when installed in a subdirectory
- Fixed an issue where admin users page pagination would not work properly
- Fixed an issue with redirecting to the home page after accepting the terms
Added:
- Added more checks to the installation (Checking if database credentials are properly entered etc.)

# V2.1.2 (11 April, 2019)
Fixed:
- Fixed an issue where the dashboard button in the admin panel would redirect to the home page when installed in subdirectory
- Fixed an issue where the logo wouldn't show in the admin panel when installed in a subdirectory
- Fixed an issue where the admin logout button wouldn't work when installed in a subdirectory
- Fixed an issue where the upload complete image wouldn't show when installed in a subdirectory
- Fixed an issue where the upload password option would always be disabled
- Fixed an issue where mobile navbar would stay open after opening clicking one of the menu items
- Fixed an issue where the installation would not properly set the url to https when installing Droppy
- Fixed a possible memory leak in the file upload library

# V2.1.1
Fixed:
- Fixed issue with admin redirect when installed in subdirectory
- Fixed issue where adding language would not add the "directory" correctly.
- Fixed issue with new language email templates not loading properly.
- Fixed issue that caused the destruct email to be sent to an empty email.
- Fixed oldtimer theme page styling
- Fixed issue with emails not showing correctly when using specific SMTP providers
Added:
- The upload button will be disabled for a second to prevent spamming
- German translation

# V2.1.0
Fixed:
- Delete_old_date was set to true by default in the config.php, this is now set to false.
- Decreased automatic cleanup of failed/incomplete uploads to 12 hours
- Fixed issue where temp files weren't purged from the temp directory
- Fixed issue pagination on admin downloads page
- Fixed password always showing "Yes" on uploads page
Added:
- The error message "Some files were too large" will disappear when removing files from the queue.

# V2.0.9
Fixed:
- Fixed cancel button translation
- Fixed alignments ad section
- Fixed ad showing on login page
- Fixed issue where you couldn't remove a recipient from the list (Upload form)
- Fixed issue where ad wouldn't keep padding on top when adding a file/recipient

V2.0.8
Fixed:
- Fixed issue where it was possible to submit upload without selecting files.
- Fixed issue with background video not scaling when changing screen width/height
- Fixed ad design (some alignment issues)
- Fixed some more issues with the email design of the sendEmailClean function
Added:
- Duration column to backgrounds page.
- You can now close the settings window by clicking the gear icon again.

# V2.0.7
Fixed:
- Fixed {start_password} and {end_password} not available in sender email.
- Fixed side window not closing on terms page
- Fixed mail logo not passed to sendEmailClean function

# V2.0.6
Fixed:
- Fixed some minor coding flaws
Added:
- Added {start_password} and {end_password} tags to email templates (All the text between these tags will not be shown when there's no password set)
- Admin panel login background

# V2.0.5
Fixed:
- Fixed issues with the upload size.
- Fixed missing popup when leaving the page while uploading.
- Fixed error not showing up when entering wrong password for upload
- Fixed error not showing up when there's an invalid login for the admin panel
- Fixed error message "no decode delegate"
- Fixed issue where some browsers weren't able to download encrypted files (file size in header was incorrect)
- Fixed the upload cancel button
Added:
- Added cache purge for browser cache.

# V2.0.4
- Fixed mouse hover on sidebar links.
- {password} email tag is back in the receivers email template
- Improved form validation
- Removed logo from mobile page
- Download page styling on mobile
- Issue where external plugin (S3, FTP) were not able to do uploads with more than 1 file.

# V2.0.3
Fixed:
- Issue where total upload size wasn't shown in the email (Caused by V2.0.2)
- Fixed issue where assets wouldn't load when Droppy is installed in a subdirectory
- Fixed email styling in outlook
- Fixed email styling on mobile
- Removed some debugging lines
- Issue where changing the default language from english to something else would cause errors to show up on different places
- Slightly improved authentication security
- Issue where website would be inaccessible/stuck while downloading.
- Fixed issue where S3 didn't show the file size while downloading.
Added:
- Option "Set default" to language page.
- Updater has been moved to external update library, with support for multiple SQL files.
- Site logo to the top of the emails
- Logout button when page is locked for upload or both download and upload
- New translation "logout"

# V2.0.2
Fixed:
- Language translation in javascript were always english (File upload alerts etc.)
- Reply-to email in the file receivers email has been changed to the sender's email address
- Fixed issue where there was no "Maximum files" alert after selecting too many files.
- Fixed issue where small file uploads (1-100 kb) would show 0 as total files and size.
- Fixed issue where modals on mobile wouldn't show on the download page
- Fixed issue where the "View terms" wasn't visible on mobile
Added:
- Some extra paddings on mobile
- Option to specify timezone (Settings -> General settings)

# V2.0.1
Fixed:
- Issue where uploads page wouldn't load in the admin panel
- Issue where the "Link" form would not load when the default has been set to "Link"
- Issue where destruct buttons would dissapear when set to "Yes"
- The accept the terms page was missing
- The installation will now the proper path to the language directories
- Fixed the path of "Here" button on the template page
- Fixed incomplete uploads cron
- Fixed files that are still uploaded even though you removed them from the file selection list.
- Fixed error message shown on the admin uploads page while someone is uploading a file.
Added:
- Option to specify the language directoy name and language name.
- Mobile version of Droppy has been added again.
- Added message column to uploads page
- Added grey border around the boxes
- Added delete_old_data option
- Added manual update option

# V2.0
New:
- Entire codebase has been rewritten from scratch
- Chunked file uploads ! (Sending files to the server in small pieces)
- New background library for smoother transitions
- Specify the length(time) of each background
- New (more secure) password hashing
- Email placeholder {expire_time} format has been changed
- Backgrounds do now have their own page in the admin panel
- Setting a default language can now be done from the language page in the admin panel
- Encrypting method for files has been changed to openssl
- File decryption will now happen while downloading a file
- Site backgrounds are now shown on the login page

Removed:
- {password} email tag has been removed
- Dropped support for PHP version lower than 7, PHP 7 or higher should be used from now on.

Fixed:
- Issue where user wasn't able to go to the download page after uploading (constantly loading until the actual upload finished processing).

# V 1.4.6 (16 October, 2017)
* Fixed: Issue where upload was not assigned to premium user
* Added: "Are you sure" message to translation files

# V 1.4.5 (31 July, 2017)
* Fixed: Issue when only 1 background image was uploaded
* Fixed: "Default email to" vulnerability
* Fixed: Theme preview links in the admin panel
* Fixed: Issue where upload progress wasn't showing when selected file was too large
* Fixed: Copy button on upload page
* Fixed: Some errors being caused by the loading of the plugins tabs
* Fixed: Issue with file deletion on report
* Added: Confirmation message on upload cancel
* Added: Arabic language file
* Removed: "Pages" tab from the admin panel

# V 1.4.4 (09 April, 2017)
* Fixed: Issue where the background video wasn't showing when it was the only available background source.
* Fixed: Admin panel vulnerability.
* Fixed: Issue that caused the "Okay" button to redirect to the wrong location.

# V 1.4.3 (19 March, 2017)
* Fixed: Issue that caused the page to become scrollable when a background video was playing
* Fixed: Issue where some themes weren't showing the upload settings sidebar correctly.
* Fixed: Improved fade-in and fade-out effect of video backgrounds.
* Fixed: Issues with filename escaping since update 1.4.0

# V 1.4.2 (09 March, 2017)
* Fixed: Issue where premium plugin pages weren't showing on the mobile page.

# V 1.4.1 (4 March, 2017)
* Fixed: Issue where "Upload not found" page was shown when the terms weren't accepted.

# V 1.4.0 (27 February, 2017)
* Added: New improved file/directory structure.
* Added: New improved upload code.
* Added: New rewrite to access the pages more SEO friendly. (E.g http://yourdomain.com/page/premium). (The old URL still works)
* Added: You are now able to add an comma separated email list to the receiver field.
* Added: Confirmation popup when user closes website while uploading.
* Added: Support for background videos (MP4 only).
* Added: File upload encryption (This is an option and by default disabled).
* Fixed: Issue with special characters in file name.
* Fixed: Installation and upload issues when MySql strict mode is enabled.
* Fixed: Issue where old rows weren&#8217;t automatically deleted from the database (if enabled).
* Fixed: Report button on mobile version.

# V 1.3.5 (14 February, 2017)
* Fixed: Vulnerabilities in the admin panel.

# V 1.3.4 (28 January, 2017)
* Fixed: Included some missing stylesheets

# V 1.3.3 (18 January, 2017)
* Fixed: Updated PHPMailer to prevent possible vulnerabilities.
* Fixed: The system will not be able create an upload with the same id anymore.

# V 1.3.2 (28 August, 2016)
* Fixed: Issue where not destroyed files where removed from the DB.
* Fixed: Issue where message was not looking correctly on the download page.
* Fixed: Issue where file size in emails was incorrectly.
* Improved: Admin panel security
* Added: Support for new plugin
* Added: Cancel upload button
* Added: You can now upload/delete backgrounds through the admin panel.

# V 1.3.1 (13 June, 2016)
* Fixed: Issue where download page was showing ?Upload not found? when the file was still processing.
* Fixed: Issue where file size was showing a negative number.
* Added: Function that will automatically remove an upload that is processing for more than 1 Day (86400 sec).
* Fixed: Some small typos, and improved coding.

# V 1.3.0 (25 April, 2016)
* Added: Italian translation
* Added: Reply-To header to the emails
* Fixed: Issue where upload form was getting taller every time a recipient was added.
* Fixed: Issue with an empty email input.
* Fixed: Issue where it wasn?t possible to allow all file types.
* Fixed: Issue where it wasn?t possible to change the language on the mobile version.
* Fixed: File sizes are now more precise (MB / KB).
* Improved: Upload speed indicator.

# V 1.2.9 (28 March, 2016)
* Fixed: Issue with Drag &#38; Drop

# V 1.2.8 (28 March, 2016)
* Added: Selected file list to mobile version.
* Added: "About us" tab to terms popup.
* Added: System requirements validation to the installation.
* Added: Updater will now remove the downloaded zip file after updating.
* Added: You can now leave the background URL inputs blank so it won?t redirect.
* Fixed: Issue where password was undefined (Always set)
* Fixed: Issue where remaining GB was incorrect after too many files were selected.
* Fixed: Issue where selected GB was incorrect.
* Fixed: Issue that was causing Safari to redirect on file selection.
* Fixed: Scrolling issue.

# V 1.2.7 (1 March, 2016)
* Added: Drag &#38; Drop functionality.
* Added: Possibility to add files from different folders/directories.
* Added: Possibility to drop a whole folder/directory.
* Added: List of selected files before uploading.
* Added: Option to remove a specific file before uploading.
* Added: ?None? as security option for the SMTP connection.
* Added: The upload section will now check the file file types before uploading.
* Added: Option to set the default email to which all uploads should go.
* Fixed: Issue where downloads were not counting.
* Fixed: Security issue with language function.
* Fixed: Issue where page crashes when language was not found.
* Fixed: Issue where background urls and images where not matching or incorrectly.
* Fixed: Issue where emails were sent to the spam folder.
* Fixed: Security issue with admin panel.
* Fixed: Issue with Turkish translation.
* Fixed: Some other small minor issues.
* Updated: Font-awesome.
* Improved: Upload system has become more ?stable?.

# V 1.2.6 (19 December, 2015)
* Added: The update.php file will now remove itself after updating.
* Fixed: Issue where uploaded files were duplicated in the tmp/ directory.
* Fixed: Weeks, days, hours and months are now translatable.

# V 1.2.5 (18 December, 2015)
* Added: Uploader can now download his/her own files.
* Added: Droppy will now remember the user?s language when sending the emails.
* Added: New improved email system.
* Fixed: Issue with errors on login page.
* Fixed: Issue with login background.
* Fixed: Issue with speed indicator.
* Fixed: Email styling for G-Mail and other email clients.
* Fixed: Empty emails when file was removed by cron job.
* Fixed: Some issues with accessing files (You are not allowed to view this file message).
* Improved: Some coding structure.

# V 1.2.4 (13 December, 2015)
* Fixed: Email messages where empty when language was not set.
* Fixed: Issue where upload could be submitted with not valid email addresses.

# V 1.2.3 (13 December, 2015)
* Added: View terms button to agree terms page.
* Added: Navbar to the mobile page (To view all the tabs).
* Added: Translatable email messages.
* Fixed: Issue where users weren?t able to visit the page while downloading.
* Fixed: Issue where accept terms was still showing up on mobile page.
* Fixed: Issue where password was always showing ?Yes? (Admin panel).
* Fixed: Issue where password field on was not checked if it was empty.
* Fixed: ?Email to? will now show the email instead of ?Droppy user?.
* Fixed: Some styling issues.
* Improved: Automatic updater.

# V 1.2.2 (20 November, 2015)
* Added: The email recipients input will now be validated and checked if empty.
* Added: New system to check the latest version.
* Added: ?Uploaded of? to translation.
* Added: Upload speed indicator
* Added: Destruction date to download page.
* Added: Notification when update server is offline
* Added: Analytics code field to general settings page.
* Added: Option to force the users to accept the terms of service.
* Fixed: Issue where destruction email shortcodes where not replaced using admin destruction.
* Fixed: Issue where upload was not downloading.
* Fixed: Issue with advertisement on mobile page.
* Fixed: Some small issues with the download header.
* Fixed: Some minor styling issues.

# V 1.2.1 (5 November)
* Fixed: Some general issues.

# V 1.2.0 (2 November)
* Added: Some functions for future plugins
* Added: New time destruction system.
* Added: Option to disable/enable password function.
* Added: System log page (Admin panel).
* Fixed: Some misspelled text.
* Fixed: Some uploading issues.
* Improved: Mobile detection.

# V 1.1.5 (5 October, 2015)
* Added: Function to add custom themes.
* Added: Plugin updater function.
* Added: Download email to download list
* Added: New (simple) theme.
* Added: Hand cursor when hovering over the background.
* Added: Default share type option.
* Added: Background is now randomised.
* Added: New admin panel design.
* Fixed: Some bug fixes.

# V 1.1.4 (21 September, 2015)
* Fixed: Bug where users weren't able to download files.
* Fixed: Some updating issues.

# V 1.1.3 (20 September, 2015)
* Added: Support for mobile/tablet uploading
* Added: ?Total downloads? value in the uploads table.
* Added: Remaining upload time while uploading
* Added: Mobile responsive
* Added: Turkish translation
* Fixed: Minor bug fixes
* Improved: Coding of the script
* Improved: Some re-designing

# V 1.1.2 (30 August, 2015)
* Fixed: Minor bug fixes

# V 1.1.1 (12 August, 2015)
* Fixed: Issues with the installation
* Fixed: Issues with automatic updater

# V 1.1.0 (12 August, 2015)
* Fixed: Some updating issues
* Fixed: Logo height issue.

# V 1.0.9 (11 August, 2015)
* Fixed: Issue when downloading multiple times.
* Fixed: Issue with Droppy logo won?t change.
* Added: Support for plugins
* Added: Automatic plugin installer
* Added: Automatic updater for Droppy (You can now update Droppy with 1 single click)
* Improved: Installation

# V 1.0.8 (17 July, 2015)
* Fixed: Issue with cron job.
* Fixed: Issue with height of upload message area.
* Fixed: Problem when 1 single background has been set.
* Fixed: Problem with secret URLs that are allocated to the receiver of the file(s).
* Added: French translation.

# V 1.0.7 (9 July, 2015)
* Added: Option to lock down the upload and/or download.
* Added: {email_list} tag.
* Added: {item_list} tag.
* Added: User can now select between multiple languages from the front page.
* Added: Advertising support.
* Added: Terms of service page.
* Added: About us page.
* Added: Copy URL button.
* Added: Function to disable the expire time.
* Added: More expire times (Months).
* Added: Reminder to change the tmp directory permissions.
* Added: Possibility to change the email receiver name.
* Added: Function to remove the added recipients
* Improved: Design of upload settings menu.
* Improved: Nearly all of the email tags are now available on all the email templates.
* Improved: Upload speed when using ?Link? function (message ?Generating Link? removed).
* Fixed: Some small email issues.
* Fixed: Max upload size will now show GB when higher than 1000MB
* Fixed: Some installation issues
* Fixed: Minor bugs.

# V 1.0.6 (10 June, 2015)
* Improved: New upload system
* Improved: New download system
* Improved: URL privacy (No emails in the URL anymore)
* Improved: Windows OS improvements
* Added: Possible to sort table views in admin panel
* Added: Possible to view all the rows in tables
* Added: Option to automatically destroy file after certain amount of reports
* Added: Option to change the password and email of the admin user
* Added: Option to restore admin password
* Fixed: Small minor bug fixes

# V 1.0.5 (4 April, 2015)
* Fixed: Minor bug fixes

# V 1.0.4 (30 March, 2015)
* Added: Upload report system.
* Added: Social button links will now open in a new tab
* Added: Variable {download_btn}.
* Added: Variable {password}.
* Added: Clickable file id to uploads and downloads table in the admin panel.
* Added: Social buttons to all pages.
* Added: Social buttons will now open into a new tab.
* Added: Email when receiver has downloaded the file(s).
* Added: Error message when file size to large.
* Fixed: File names in a zip file will now be their old name.
* Fixed: Problems that not all the files were zipped into one zip file.
* Fixed: Some meta tags improvements.
* Improved: Better styling for the receivers section on upload page.
* Improved: Some styling and error messages.
* Improved: Responsive improvements.
* Improved: Uploading function.

# V 1.0.3 (11 March 2015)
* Fixed: Bug droppy not working with subdirectory.
* Fixed: Some email template character coding.
* Fixed: Some little bugs.
* Added: {email_to} tag to the email templates.
* Added: Social buttons to the download page.
* Added: Option to admin panel to update your current url.
* Change: Made some small changes to the translation.

# V 1.0.2 (8 March, 2015)
* Fixed: "-" and "," not working propperly in filename.
* Fixed: Social logo settings not working properly.
* Fixed: Upload settings section not closing/opening in some browsers.
* Fixed: Success message when user clicks the download button.
* Fixed: UTF-8 coding in email templates settings (Russian language etc.)
* Fixed: Translation bug.
* Added: Multiple website backgrounds with live update after set seconds.
* Added: Clickable background url per background image.
* Added: Email when destruct upload from admin panel
* Added: German translation.
* Added: Function to disallow specific file types
* Added: Download page in the admin panel.
* Added: {password} option added to email templates
* Changed: Replaced the social buttons (For future plans).

# V-1.0.1 (3 March, 2015)
* Fixed: Some errors and bug fixes.
* Fixed: Email bug.
* Fixed: Translation bug.

# V-1.0 (2 March, 2015)
* Release
