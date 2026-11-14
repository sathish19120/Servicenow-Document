# Servicenow-Document

## Here is a complete ServiceNow Developer 5+ years interview question checklist. Prepare these topics well; they cover most interviews.
1. Introduction and project experience
1. Tell me about yourself and your ServiceNow experience.
2. Explain your current/last project architecture.
3. Which ServiceNow modules have you worked on?
4. What are your daily responsibilities as a ServiceNow Developer?
5. Explain one requirement you developed end to end.
6. Explain one production issue you resolved.
7. How do you gather requirements and estimate effort?
8. How do you move changes from Dev to UAT and Production?
2. ITSM concepts
9. What is ITSM?
10. Explain Incident Management.
11. Difference between Incident, Problem, Change, and Request.
12. What is Major Incident Management?
13. What is Change Management? Explain Normal, Standard, and Emergency change.
14. What is CAB?
15. What is an SLA? What are SLA start, pause, stop, and breach conditions?
16. What is Service Catalog?
17. Difference between Catalog Item, Record Producer, and Order Guide.
18. What are Requested Item (RITM), Catalog Task (SCTASK), and Request (REQ)?
19. Explain the request lifecycle from submission to closure.
3. CMDB and Discovery
20. What is CMDB?
21. What is a Configuration Item (CI)?
22. Difference between Asset and CI.
23. What is the CMDB relationship table?
24. What is CI class hierarchy?
25. What is CMDB Health—completeness, correctness, and compliance?
26. What is ServiceNow Discovery?
27. What are MID Server, credentials, and patterns?
28. Explain Discovery process from scan to CI update.
29. What is Identification and Reconciliation Engine (IRE)?
30. What happens when duplicate CIs are discovered?
31. Difference between Discovery and Service Mapping.
4. Scripting fundamentals
32. Difference between client-side and server-side scripting.
33. What are the types of Client Scripts?
34. Explain onLoad, onChange, onSubmit, and onCellEdit.
35. What is g_form? Give examples.
36. What is g_user?
37. What is g_scratchpad and when do you use it?
38. What is a Business Rule? Explain Before, After, Async, and Display Business Rules.
39. Difference between Before and After Business Rule.
40. When do you use an Async Business Rule?
41. What are current and previous?
42. What is GlideRecord? Write a query example.
43. Difference between get() and query() in GlideRecord.
44. Difference between addQuery() and addEncodedQuery().
45. How do you insert, update, and delete a record using GlideRecord?
46. How do you avoid GlideRecord queries inside loops?
47. What is a Script Include?
48. Difference between client-callable and server-side Script Include.
49. What is GlideAjax? Explain client-to-server communication.
50. Difference between GlideAjax and getReference().
51. What is a UI Action?
52. What is a UI Policy? Difference between UI Policy and Client Script.
53. What is a Data Policy? Difference between Data Policy and UI Policy.
5. Security and access control
54. What is an ACL?
55. How does ACL evaluation work?
56. Difference between table-level and field-level ACL.
57. What is the difference between roles, groups, and users?
58. How do you restrict a user from editing one field?
59. How do you debug an ACL issue?
60. What is impersonation, and when do you use it?
61. What is domain separation?
6. Service Catalog and Flow Designer
62. How do you create a Catalog Item?
63. What are catalog variables and variable sets?
64. What are variable types: reference, lookup select box, list collector, and MRVS?
65. How do you make a catalog variable mandatory or read-only dynamically?
66. What is a Catalog Client Script?
67. What is a Catalog UI Policy?
68. How do you create approval for a catalog request?
69. Difference between Workflow and Flow Designer.
70. What are Flow, Subflow, Action, Trigger, and Spoke?
71. How do you handle errors in Flow Designer?
72. How do you prevent a flow from running repeatedly or recursively?
73. How do you call a subflow from a flow?
74. Explain a laptop-request catalog item end to end.
7. Integration and APIs
75. What types of ServiceNow integrations have you worked on?
76. Difference between REST and SOAP APIs.
77. What is a REST Message?
78. How do you call an external REST API from ServiceNow?
79. What is a Scripted REST API?
80. How do you secure an integration?
81. Explain OAuth, Basic Authentication, API key, and mutual TLS.
82. How do you send data from ServiceNow to another application?
83. How do you receive data into ServiceNow from another application?
84. What is IntegrationHub?
85. What is a MID Server’s role in integrations?
86. How do you handle failed API calls, retries, and error logs?
87. How do you avoid exposing passwords or tokens in scripts?
8. Notifications, email, and reports
88. How do you configure email notifications?
89. What are notification conditions, recipients, and email templates?
90. How do you prevent duplicate notifications?
91. What are inbound email actions?
92. How do you create an incident from an incoming email?
93. Difference between Report, Dashboard, and Performance Analytics.
94. How do you create a report for open incidents by assignment group?
95. How do you schedule a report?
9. Deployment and production support
96. What is an Update Set?
97. What changes are not captured in Update Sets?
98. What is the correct deployment process: Dev → Test/UAT → Production?
99. What is Update Set preview? What are collisions?
100. How do you resolve an Update Set conflict?
101. What is the difference between Commit and Back Out?
102. What is a clone? What happens to changes in a sub-production instance after a clone?
103. How do you protect important configuration before an instance clone?
104. How do you debug a production issue safely?
105. What is system logging and how do you use it?
106. Difference between gs.info(), gs.warn(), and gs.error().
107. What is Script Tracer?
108. What is Debug Business Rule?
10. Scenario-based questions — very important for 5+ years
109. A field must be mandatory only when Priority is Critical. How will you implement it?
110. A user can see a record but must not update it. How will you configure this?
111. An Incident should automatically assign to Network Team when Category is Network. How will you implement it?
112. A catalog item needs manager approval and then fulfilment tasks for IT. Explain your design.
113. A flow creates duplicate tasks. How will you troubleshoot and prevent it?
114. A Business Rule is slowing down Incident updates. How will you optimize it?
115. A user cannot see a field even though they have the correct role. How will you troubleshoot?
116. An integration is failing only in Production. What checks will you perform?
117. Discovery creates duplicate server CIs. How will you solve it?
118. A user accidentally updated 10,000 records. How will you handle it?
119. A change is urgent and needs immediate production deployment. What process will you follow?
120. How do you ensure code quality, testing, rollback, and documentation before production deployment?
Prepare questions 1–31 first, then scripting questions 32–53, because those are asked most often for a developer role.

## Focus on these 25 high-priority questions first:
1. Self-introduction
2. Your ServiceNow project and responsibilities
3. Incident vs Problem vs Change vs Request
4. Catalog Item vs Record Producer vs Order Guide
5. REQ, RITM, and SCTASK
6. CMDB, CI, Asset vs CI
7. Discovery, MID Server, IRE
8. Client Script types
9. Business Rule types
10. Client Script vs Business Rule
11. UI Policy vs Data Policy
12. GlideRecord basics
13. Script Include and GlideAjax
14. ACL and ACL debugging
15. Roles, groups, users
16. Catalog Item end-to-end development
17. Flow Designer and approval flow
18. Workflow vs Flow Designer
19. REST API integration basics
20. Update Set and deployment process
21. Update Set preview/conflict
22. Instance clone
23. One production issue you resolved
24. One catalog item you developed
25. One difficult scenario and how you solved it
