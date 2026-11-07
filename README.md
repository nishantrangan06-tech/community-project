# community-project
Evaluate the accessibility of at least 10 government or public-service websites using WCAG guidelines, develop accessibility improvement recommendations, and implement a prototype demonstrating compliance improvements.

Things to do:      

Phase 1: Select and Evaluate 10+ Public-Service Websites  
Phase 2: Analyze and Document Findings (POUR Model)   
Phase 3: Develop Accessibility Improvement Recommendations   
Phase 4: Implement a Compliance Prototype  

note : We can do the website for only one gov website to show how it should be  

Gov Website list :  
      1)Bruhat Bengaluru Mahanagara Palike (BBMP) Portal (http://www.bbmp.gov.in)  
	           -> What to audit: Citizen property tax payment gateways, trade license renewals, and grievance filing.  
	           -> Common Gaps: Dynamic pop-up notices lacking keyboard control focus, nested dropdown navigation links skipping screen reader announcements, and                                unlabelled captcha fields.    
      ---------------------------------------------------------------------------------------------------------------------------------------------------   
      2)Municipal Corporation of Greater Mumbai (MCGM / BMC)  (https://www.mcgm.gov.in)  
	           -> What to audit: Water bill payments, building plan approvals, and interactive spatial maps.  
	           -> Common Gaps: Complex iframe maps that act as keyboard traps, highly nested portal architecture, and decorative icons missing clear null alt=""                                text tags.  
      --------------------------------------------------------------------------------------------------------------------------------------------------     
      3)Karnataka State Road Transport Corporation (KSRTC)  (https://www.mcgm.gov.in / https://portal.mcgm.gov.in)
	           ->What to audit: Interactive seat selection map matrix, search filters, and checkout workflows.  
	           ->Common Gaps: Bus seat layouts reliant solely on colour visual state cues (e.g., green for available, red for booked) failing WCAG 1.4.1 (Use of                                 Color), and failure to maintain logical focus order when selecting dates.    
      --------------------------------------------------------------------------------------------------------------------------------------------------   
      4)Maharashtra State Road Transport Corporation (MSRTC)  (maharashtra.gov.in.)
	           ->What to audit: Multi-language toggles, timetable lookups, and bus booking steps.  
	           ->Common Gaps: Missing alternative language metadata tags (failing screen reader pronunciations), poor typographic scaling layout shifts at 200%                                  zoom, and unlabelled booking input fields.  
      ---------------------------------------------------------------------------------------------------------------------------------------------------  
      5)Bangalore Electricity Supply Company (BESCOM)  (https://bescom.karnataka.gov.in/.)  
	           -> What to audit: Digital bill downloads, electricity calculation metrics, and registration forms.  
	           -> Common Gaps: Text compressed within raster images (failing WCAG 1.4.5), inline error handling missing real-time screen reader announcements, and                 legacy, text-heavy tabular rows.  
      --------------------------------------------------------------------------------------------------------------------------------------------------  
      6)Mahanagar Gas Limited (MGL)  (mahanagargas.com.)  
	           -> What to audit: Commercial piped gas billing history, customer sign-in portals, and emergency reporting tabs.  
	           -> Common Gaps: Inadequate contrast ratios on subtle light blue elements (failing the 4.5:1 text ratio requirement), and modal popup windows that    do                      not catch focus upon opening.  
      -------------------------------------------------------------------------------------------------------------------------------------------------   
      7)Ministry of Consumer Affairs, Food and Public Distribution  (consumeraffairs.nic.in.)  
	           -> What to audit: National Consumer Helpline links, grain allocation distribution statistics, and policy circulars.  
	           -> Common Gaps: Scanning text missing correct heading level structure (H1–H6), and downloadable PDF advisories completely lacking document semantic                      tags.  
      -------------------------------------------------------------------------------------------------------------------------------------------------  
      8)Ministry of Social Justice and Empowerment  (socialjustice.gov.in.)  
	           -> What to audit: Scheme distributions, disability scholarship updates, and press releases.  
	           -> Common Gaps: Scanning text loops that cannot be paused, embedded image flyers without alt descriptors, and lack of operational skip-to-content                             links.  
      -------------------------------------------------------------------------------------------------------------------------------------------------   
      9)Staff Selection Commission (SSC)  (ssc.gov.in.)  
	           -> What to audit: Candidate log-in dashboard platforms, exam registration forms, and answer key downloads.
	           -> Common Gaps: Multi-step workflow form fields timed out without notice notifications, focus tracking failure across interactive radio buttons,                            and complex data tables without explicitly coded table headers (<th>).  
      -------------------------------------------------------------------------------------------------------------------------------------------------    
      10)Central Board of Secondary Education (CBSE)   (cbse.gov.in.)  
	           -> What to audit: Board examination result gateways, circular repositories, and school affiliation trackers.  
	           -> Common Gaps: High-volume usage hours display complex tabular student roll-number data frameworks lacking ARIA descriptive markers, unlabelled                                search inputs, and flashing text links.  
