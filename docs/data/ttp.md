# Techniques, Tactics and Procedures (TTP)

!!! info
    These TTPs are based on the Department of the Air Force's (DAF) SharePoint guidance. Some of the tips based may be applicable only to DAF or SharePoint. However, the principles may cross into other collaboration and storage solutions such as Nextcloud and Google Workspace.

## Collaboration

<div class="grid cards" markdown>

-   __Collaborate with DISCUSSION feature__ <span style="color: white; background: green; border-radius: 5px;">&nbsp;CL-01&nbsp;</span>

    ---

    AF personnel will use the DISCUSSION in SharePoint Online instead of email capability for AF internal threaded discussions.  If an email starts to turn into a threaded discussion (after two forwards or replies), the lead team member should put it into a discussion board as soon as possible in order to preserve the intent of the discussion points.

-   __Collaborate with ISSUES/TASKS List feature__ <span style="color: white; background: green; border-radius: 5px;">&nbsp;CL-02&nbsp;</span>

    ---

    Personnel will use the ISSUES/TASKS list capability in the SharePoint Online instead of email to do taskers or resolve internal issues in order to reap the benefits of tracking the progress properly. There is also Nextcloud Tasks, Jira, Github issues, and Microsoft Planner that also provide the same capability.

-   __Collaboration - Real-Time Co-Authoring / Check-In Check Out__ <span style="color: white; background: green; border-radius: 5px;">&nbsp;CL-03&nbsp;</span>

    ---

    SharePoint Online &amp; Microsoft365 include the Real-Time Co-Authoring feature, in which multiple users can collaborate and make edits to a document simultaneously with updates/edits shown in real-time. This is the recommended method for document collaboration. The Check-Out / Check-In feature is also still available which, if used, the user must reserve it prior to editing (this will keep the integrity of the edits intact), edit it in the native application, use the Revision capability inherent in most MS Office applications to show others how the document has changed, check it in once editing is complete, and fill in the comment box after Check-in, which in effect is the automated CHANGE PAGE feature of SharePoint Online. The AF is used to emailing or downloading a document and uploading/sending it back for someone to consolidate comments. True collaboration means we all touch the exact same copy of a document, which means you can overwrite someone else’s work if you aren’t following basic rules. Sometimes a document will appear checked out even after you checked it in.  Refresh your web site and it should clear the cache and present the correct status.

-   __Announcements/News Best Practice__ <span style="color: white; background: green; border-radius: 5px;">&nbsp;CL-04&nbsp;</span>

    ---

    Initially Organizations should focus on posting News and/or Announcements (relevant to the organization) on the organizational site in place of sending out emails.  This puts everything in one place -  allows the expiration date for a clean display, and an Information Management policy could be established to delete “old” announcements.
</div>

## Document Management

<div class="grid cards" markdown>

-   __Creating Libraries vs. Folders__ <span style="color: black; background: silver; border-radius: 5px;">&nbsp;DM-01&nbsp;</span>

    ---

    It is best practice to create more libraries instead of making more folders with deeper structures. Horizontal is better than vertical due to navigation, search, and URL limitations.

-   __Only Handle Information Once (OHIO) Principle__ <span style="color: black; background: silver; border-radius: 5px;">&nbsp;DM-02&nbsp;</span>

    ---

    A document or information should be born, live, change, and die (be made a record for dispositioning) from a single location. The document will generally be created, edited, finalized and deleted from the Team site where it was produced.  Once it is initially moved to SharePoint for collaboration, all other copies on `C:\` drive, shared drives, etc. **MUST BE DELETED!** It is understood that there are cases where you will need to put the document on some media other than SharePoint.  However, SharePoint is the holder of the official working copy of the document.  Any document not directly retrieved from SharePoint should be treated as other than official and not configuration controlled. The exception to this TTP is when a document becomes an official record. At that time, the official copy is located in the organization's official Records Management location and a working copy (or link to the record) may still reside in SharePoint Online.  This allows for reuse of the document without retrieval from the SharePoint Online site. Currently, SharePoint Online does not have an official Records Management capability.
</div>

## General

<div class="grid cards" markdown>

-   __Everyone has access and shares (Broad Visibility)__ <span style="color: black; background: orange; border-radius: 5px;">&nbsp;GL-01&nbsp;</span>

    ---

    A key concept in the usage of SharePoint Online is that information needs to be shared with all people who need access to it. The information we generate doesn’t belong to us, it belongs to the AF, the DoD, the US Government, and ultimately the US Populace. ~~For Official Use Only (FOUO)~~ Controlled Unclassified Information (CUI) is NOT enough to lock down information. It means DoD ONLY. However, this open-access philosophy also recognizes that there are laws, regulations, and policies that restrict the dissemination of certain types of information. Moreover, all SharePoint users need to understand and adhere to the dissemination restrictions. There are many types of information to which access restrictions apply and some of the classifications are Privacy Act Information, Source Selection Sensitive, Scientific and Technical Information (STINFO) (e.g., weapon system Technical Orders), Intellectual Property (Company Proprietary, Trade Secrets, etc.), and Information subject to the Foreign Disclosure and/or Export Control Laws. Every organizational site or team site front page needs to be open to all. The Site Visitors group should contain the "Everyone but external users" group, which is all personnel in the AFNet Active Directory. This will maximize collaboration and let people know you exist as a team or an organization.  It will also let users see who the leadership or POCs are to find out more about that organization or team. It is HIGHLY encouraged to leave the organizational branding in place on organizational site collections.

-   __Sending URLs via Email Vice Attachments__ <span style="color: black; background: orange; border-radius: 5px;">&nbsp;GL-02&nbsp;</span>

    ---

    Documents within an enclave accessible by all should no longer be sent via email.  URL links to the document should be sent via email instead.  If you need to send a document to an individual outside the organizational permission levels, you may use the `Share` feature. The user should ensure visitor access to the document only and not grant access to the entire list, library, site or site collection unless it is appropriate to do so.

-   __Keeping Original Format__ <span style="color: black; background: orange; border-radius: 5px;">&nbsp;GL-03&nbsp;</span>

    ---

    Maintain official records originated electronically (e.g., e-mail, correspondence, and presentations), in original electronic format. The metadata associated with the document is legally as important as the content.  Printing out emails loses metadata, as does saving as a text file.  Save all emails in Outlook Message Format (.msg)

-   __Versioning__ <span style="color: black; background: orange; border-radius: 5px;">&nbsp;GL-04&nbsp;</span>

    ---

    Versioning can be set for each document library and lists. By default, document libraries created on SharePoint Online have versioning enabled for 500 major versions. By default, lists created on SharePoint Online do not have versioning enabled.   Having versioning enabled and set to at least five (5) major versions is strongly recommended, since restores of sites in SharePoint Online from backups may not be possible. There are three choices for versioning 1) no versioning, 2) major versions only, and 3) major and minor versions.  The "major version only" setting means that each version is saved to the server and viewable to anyone with "read" or greater privileges.  The "major and minor versions" setting can be used in a collaborative model where you want to have some people working on a "draft" version, while other people can only see the "published" versions.  People with "read" privileges only see the major (a.k.a. published) versions.  People with "contribute" or greater privileges see (and can edit) the minor versions. Making a document a "major" version effectively publishes it for all persons with "read" or greater privileges to see. Both major and minor versions can be limited in number.  Not every document library will need both major and minor versions.

-   __Provisioning and Deletions__ <span style="color: black; background: orange; border-radius: 5px;">&nbsp;GL-05&nbsp;</span>

    ---

    All new site collections for SharePoint Online must be requested through the New Site Request process and utilize the naming conventions referenced in `TTP NC-03`. Any user may enter a request for a new SharePoint Online site collection but all requests are approved by the point of contact (POC) for the respective organization.  Likewise, all site collection deletes (regardless of reason) must be coordinated through the Service Request process. Only Site Collection Administrators (SCAs) for the site in question may submit a deletion request.
</div>

## Naming Conventions

<div class="grid cards" markdown>

-   __FILE Naming Conventions__ <span style="color: black; background: cyan; border-radius: 5px;">&nbsp;NC-01&nbsp;</span>

    ---

    File names should be permanent upon creation, so make it meaningful from the start.  Never end a file or folder name with "_file" or "_files."  This is reserved by Microsoft and if used by you, will be made hidden by the system.

-   __Naming Libraries__ <span style="color: black; background: cyan; border-radius: 5px;">&nbsp;NC-02&nbsp;</span>

    ---

    Be clear and concise when naming document libraries. Ensure that you can differentiate them from other libraries. This allows for easy recognition from anywhere - remember SharePoint Online can be accessed from many MS products and your desktop.  Keep in mind there are limits to the length of a URL so you don't want to make these library names too long.

-   __Site Provisioning Naming Conventions__ <span style="color: black; background: cyan; border-radius: 5px;">&nbsp;NC-03&nbsp;</span>

    ---

    All team site collections in AF SharePoint Online will use the following naming convention `https//usaf.dps.mil/teams/<Project-or-Program-Name>`. Do not put office symbols in team site URL's. Use your program or project name or request a numbered URL.  All organizational site collections in AF SharePoint Online will use the following naming convention `https//usaf.dps.mil/sites/<Organization-Name>`. When choosing a name for the last portion of your URL, keep these items in mind  If migrating from the AF SharePoint On-Premise environment at the Wright-Patterson APC, we recommend keeping your numbered site (1xxxx or 2xxxx) for the name portion of the URL (e.g. `https//usaf.dps.mil/teams/16497` or `https//usaf.dps.mil/teams/28532`).- Provides a consistent name for your users.- Guarantees there will not be a name clash (someone else already using it).You may change the URL name of your new or migrating site collection if you wish. Keep it simple, but descriptive. The following rules must be observed- Can use all lowercase, an abbreviation or CamelCase in the spelling of the URL name.- Do not use spaces in the name; instead use the dash character (“-”) if you wish to separate words.- Do not use any other special characters in the URL name.- Do not use very common Org names in your teams site collections (FM, PK, LS, etc.) or names that could change during the scope of your project or program.- Minimum of three (3) alphanumeric characters  (e.g. `https//usaf.dps.mil/teams/SOS`)- Maximum of 20 alphanumeric characters (e.g. `https//usaf.dps.mil/teams/ProjABCD` or `https//usaf.dps.mil/teams/Prog-ABCDE`)- All named URLs are first come, first served.  Requests for names already in use will not be honored.Once the site collection has been created, the top level URL (site collection) is permanent and will not be changed.
</div>

## Organizational Site

<div class="grid cards" markdown>

-   __Using the Org Branding Template__ <span style="color: white; background: red; border-radius: 5px;">&nbsp;OS-01&nbsp;</span>

    ---

    The organizational branding template should not be changed.  A site owner should change the logo or picture on the right side, but the rest should stay the same.  The banner on the bottom is mandated, and the Support Center link above the logo is the user connection to help and support. Site owners may add lots of content BELOW the standard webparts or on PAGES attached to the community site, but should not change the org site standard webparts  This will ease training and the finding of information.
</div>

## Permissions

<div class="grid cards" markdown>

-   __Default permissions setting__ <span style="color: white; background: blue; border-radius: 5px;">&nbsp;PS-01&nbsp;</span>

    ---

    Sites are created with 3 default permission groups.  The 3 main groups are Owners, Members and Visitors. **SharePoint Online (SPO) does not protect data. Information owners protect data.** SPO only facilitates the protection of the data. Used properly, SharePoint Online Permissioning structures can easily be used to safeguard information. `TTP GL-01` (Everyone has access and shares [Broad Visibility]) takes precedence. There are many types of information to which access restrictions apply and some of the classifications are- `Privacy Act Information`- `Scientific and Technical Information (STINFO)` (e.g., weapon system Technical Orders)- `Intellectual Property` (Company Proprietary, Trade Secrets, etc.)- Information subject to the Foreign Disclosure and/or Export Control Laws- Source Selection Sensitive PII/~~FOUO~~ CUI data IS allowed on SharePoint as long as it is permissioned properly and visible only to those with a need-to-know. SPO provides encryption at rest.

-   __Membership for Whole Organization__ <span style="color: white; background: blue; border-radius: 5px;">&nbsp;PS-02&nbsp;</span>

    ---

    The best permissions to give the organization and all its subsites is full membership to the ORG ALL active directory group.  This enhances collaboration across the organization from day one.  For instance, in `AFMC A6/7`, there are eight divisions, `A6X`, `A6O`, `A7A`, `A7M`, `A7R`, `A7P`, `A7O`, `A7S`.  We could only let AFMC `A7P` All have membership to the `A7P` org site but what if they need to have `A6X` comment on something they are working on for a spreadsheet or for a document?  It is far easier to let `AFMC A6/7` All have membership to `A7P` than to have employees scream that they can't share and that they don't want to put stuff on the `A6/7` site just to share.  This permissions structure repeats the ills of the shared drive - something we need to avoid in a collaborative environment.

-   __Documenting Need to Know__ <span style="color: white; background: blue; border-radius: 5px;">&nbsp;PS-03&nbsp;</span>

    ---

    To safeguard controlled unclassified information (CUI), restrict it at site or list/library level.  Avoid restricting at the folder level. Never restrict at a document/item level. Sites should only be restricted if entire site content is sensitive (source selection team, personnel management). Best application for unique permissions is at list/library level. When restricting a list/library, use TTP NC-02 (Naming Libraries), but also ensure that the rationale, the need to know, is well documented, whether in the description or a document in the list/library. For example, in the description of a library locked down due to STINFO information This library contains STINFO information concerning the FA-99 Engine design and drawings.  It is not open to the general AF populace nor is it open to contractors. The need to know consists of personnel in the role of FA-99 engineer or FA-99 program management.  The site group "FA-99 Engineers" has contribute, the site group "FA-99 PMO" has read, the site group "FA-99 Owners" has full control.

-   __Site Owner Privileges__ <span style="color: white; background: blue; border-radius: 5px;">&nbsp;PS-04&nbsp;</span>

    ---

    Every site owner should be knowledgeable in the management of a site and the permissioning of sites, libraries, lists, and folders.  Every site owner shall follow the TTPs and other SharePoint Online guidance as found on the user support center or the SharePoint Online Training (SPOT) site. Site owners will have full control of a site.  They have the privileges to create Lists and Libraries, modify and control permissions, create and edit pages and the overall structure/functionality of the site. Owners will be responsible for building the site groups/permissions as well as granting group accesses.

-   __Member Privileges__ <span style="color: white; background: blue; border-radius: 5px;">&nbsp;PS-05&nbsp;</span>

    ---

    Members have privileges to view, insert, edit, and delete items and documents. Members groups should be given “*Contribute*” access to the site. In SPO, the default access level for members is “*Edit*” and should be changed to “*Contribute*”.  Contribute access have sufficient permissions to support collaboration. See `PS-02` (Membership for Whole Organization).

-   __Visitors Privileges__ <span style="color: white; background: blue; border-radius: 5px;">&nbsp;PS-06&nbsp;</span>

    ---

    Visitors have privileges to view items and documents. Visitors groups should be given “*Read*” access to the site. The Visitors group should contain the `Everyone but external users` group, which is all personnel in the AFNet Active Directory. See `GL-01` (Everyone has access and shares [Broad Visibility]).
</div>

## Records Management

<div class="grid cards" markdown>

-   __Folder Structure__ <span style="color: black; background: yellow; border-radius: 5px;">&nbsp;RM-01&nbsp;</span>

    ---

    The keeper of a document library shall go **no further than four** (4) folders down.  Naming conventions and metadata can help handle separations.  This is to avoid building a folder for a single document or hitting the URL character limitations.  Proper naming conventions and good metadata act as natural separators.  Search is the primary discovery method, not navigation. It usually takes longer to build folders than it does to put in metadata. **NEVER** name folders with a person's name unless it is a personnel site and the data in the folder is all about them. People come and go, functions remain.
 
</div>

## Team Site

<div class="grid cards" markdown>

-   __Collaborative Work Placement__ <span style="color: white; background: purple; border-radius: 5px;">&nbsp;TS-01&nbsp;</span>

    ---

    Collaborative work will go on the appropriate Wing, Group, Squadron, or IPT Team Site Collections.  These collaboration sites are meant for a particular IPT or activity such a Combined Federal Campaign.  All work associated with that IPT, project, program, activity should be found on the team site. Collaboration Site Collections  are focused on broadcasting or communicating a message to a wide audience and view topics of common interest. Members can browse and discover relevant content by exploring categories, sorting discussions, by popularity or by viewing only posts that have a best reply.Organizational Site Collections are for information about the organization – its mission, people, etc.  Leave and TDY schedules, organizational calendars, POCs, and announcements go here.

-   __Site Owner Designation__ <span style="color: white; background: purple; border-radius: 5px;">&nbsp;TS-02&nbsp;</span>

    ---

    Owners have full control of the site and should be a designated person (an executive officer or admin assistant).  Owners are a key user, who is responsible for maintaining and managing the site and its contents. It is recommended that organizations use appointment letters to designate Site Owners as necessary.

-   __Maintaining Permissions__ <span style="color: white; background: purple; border-radius: 5px;">&nbsp;TS-03&nbsp;</span>

    ---

    The site owner will establish and maintain the file access rights/privileges for the site.  Recommend that the site owner properly handle site level permissions with the groups provided - members, owners, and visitors.  These can be renamed for ease of understanding WHY these people have these permissions.  Members have contribution rights - read, write, edit, delete, to the lists and libraries, folders and documents.  They can't change the look and feel of the site.  Visitors (generally all AF users) can read only and the org or team sites main page should ALWAYS be open to visitors - they have the right to know you exist and who you are even if they don't have rights to the data you steward.  Owners have full control of the site's look and feel but should keep branding intact for organizational sites at a minimum.If you have data needing protection (see `GL-01` [Everyone has access and shares (Broad Visibility)], `PS-01` [Default permissions setting]), PROTECT IT!  Lock at the library or list level only - SharePoint Online allows locking to the folder and file level but this will get the site owner into permissions chaos quickly.  See `PS-03` (	Documenting Need to Know) for use of restricted libraries.

-   __Creating Sites__ <span style="color: white; background: purple; border-radius: 5px;">&nbsp;TS-04&nbsp;</span>

    ---

    Top Level sites are created with the “Site Provisioning” process, where the initial Site Collection Administrators are identified.Site Admins/Owners can create subsites as needed.  If a function needs announcements, needs its own library structure, needs links and discussion threads, then a new subsite is appropriate.  If these things are not needed, a library is probably the best bet. Keep in mind, subsites should be created laterally/horizontally across the site collection in order to maintain the site structure, prevent excessive deepening of site hierarchy, and to keep URLs short. Subsites should reside directly under the site collection sites.  It is not recommended to make subsites within subsites. Team Site collections will have annual renewal requirements.

-   __Number of Site Owners__ <span style="color: white; background: purple; border-radius: 5px;">&nbsp;TS-05&nbsp;</span>

    ---

    Each site should have at least two (2) people assigned as site Owners to ensure continuity of operations.  There should never be more than four (4) site owners. MAJCOMs should include an in/out processing procedure for all designated site collection administrators.

-   __Banners on Team Site__ <span style="color: white; background: purple; border-radius: 5px;">&nbsp;TS-06&nbsp;</span>

    ---

    Banners across the tops of teams or communication sites are highly discouraged. Banners take up valuable real estate on the community home page and take up valuable bandwidth.  The Logo space on the right hand side is the proper location for the activity to show its shield, picture of its system, or other logo.
</div>