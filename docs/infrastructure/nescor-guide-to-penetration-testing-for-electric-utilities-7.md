---
layout: default
title: 7 Server Application Penetration Tasks     
parent: §  NESCOR Guide to Penetration Testing for Electric Utilities 
grand_parent: Infrastructure 
nav_order: 70 
---
<style>
.dont-break-out {
  /* These are technically the same, but use both */
  overflow-wrap: break-word;
  word-wrap: break-word;

  -ms-word-break: break-all;
  /* This is the dangerous one in WebKit, as it breaks things wherever */
  word-break: break-all;
  /* Instead use this non-standard one: */
  word-break: break-word;
}
</style>

<div class="dont-break-out" markdown="1">
1. TOC
{:toc}

## 7 Server Application Penetration Tasks
This section pertains to the testing of applications that are executing on the control server. Standard software testing guidelines such as the Open Web Application Security Project (OWASP) Testing Guide can be leveraged to perform this task. The overarching goal is to identify vulnerabilities in applications that allow an attacker to gain access to the control server. The following table will help map specific components that should be considered for each Smart Grid product domain.

<table cellpadding="0" cellspacing="0">
	<tbody>
		<tr>
			<td valign="top">

				<p align="justify">AMI</p>
			</td>
			<td valign="top">

				<p align="justify">● Web based user interfaces on the headend servers and MDMS&nbsp;</p>

				<p align="justify">● Web servers hosted on headend servers and MDMS&nbsp;</p>

				<p align="justify">● Traditional applications that communicate to a central server via web services such as REST and SOAP.</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DR</p>
			</td>
			<td valign="top">

				<p align="justify">● DR server application on the DRAS&nbsp;</p>

				<p align="justify">● DR client application on the gateway&nbsp;</p>

				<p align="justify">● Energy resource control applications on the BAS&nbsp;</p>

				<p align="justify">● All management applications, web based user interfaces, and web servers hosted on the servers</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DER</p>
			</td>
			<td valign="top">

				<p align="justify">● Web based user interfaces on DER Management Server&nbsp;</p>

				<p align="justify">● Web service interfaces on DER Management Server&nbsp;</p>

				<p align="justify">● Web based user interfaces on Customer Energy Management System&nbsp;</p>

				<p align="justify">● Traditional client applications that communicate with the DER Management Server via web services such as REST and SOAP.</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">DGM</p>
			</td>
			<td valign="top">

				<p align="justify">● Web based user interfaces on&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ Management servers for each vendor&rsquo;s DGM devices&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ DGM Server&nbsp;</p>

				<p align="justify">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; ○ occasionally on some field devices themselves&nbsp;</p>

				<p align="justify">● Web services (SOAP or REST) between servers and occasionally to field devices or distributed substation servers&nbsp;</p>

				<p align="justify">● Traditional client applications that communicate with the DGM Server or vendor management servers via web services such as REST and SOAP.</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">ET</p>
			</td>
			<td valign="top">

				<p align="justify">● EV management applications&nbsp;</p>

				<p align="justify">● Web based user interfaces on the EV management server&nbsp;</p>

				<p align="justify">● Web based user interfaces on the gateway</p>
			</td>
		</tr>
		<tr>
			<td valign="top">

				<p align="justify">WAMPAC</p>
			</td>
			<td valign="top">

				<p align="justify">● WAMPAC applications and other web based user interfaces and web servers hosted on PDCs&nbsp;</p>

				<p align="justify">● WAMPAC datastores&nbsp;</p>

				<p align="justify">● Phasor gateways&nbsp;</p>

				<p align="justify">● Synchrophasor management servers&nbsp;</p>

				<p align="justify">● WAMPAC software installed on commodity operating systems&nbsp;</p>

				<p align="justify">● PMUs with web interfaces.</p>
			</td>
		</tr>
	</tbody>
</table>


Figure 7a below shows the overall process flow of the task sub-categories in this section. The figure shows the three task sub-categories must be performed in series. As in previous diagrams in this document, the colors represent the recommended likelihood that a utility should consider performing these task sub-categories, and the relative level of expertise required.

Figure 7a: Server Application Subcategory Flow

Each subcategory below will include a similar diagram depicting the process flow and recommended likelihood to perform for each task. 

**Suggested Tools:** 

- Web application penetration testing software such as found on the Samurai Web Testing Framework (SamuraiWTF) project

### 7.1 Application Mapping

This subcategory of penetration tasks focuses on the gathering of information and allows the tester to gain a firm understanding of the user interface or web service functionality and design.

Figure 7.1a: Application Mapping Task Flow

#### 7.1.1 Application and Platform Fingerprinting

***Level of Effort:*** Low

***Task Description:*** Use tools to query the application service to identify the platform type and version hosting the application. (Such as Apache and Tomcat)

***Task Goal:*** Identify the application server and technologies used to host the application.

#### 7.1.2 Functional Analysis 

***Level of Effort:*** Low 

***Task Description:*** Gain an understanding of the application from the user’s perspective. Explore the application and identify major functionality and features exposed to the user. Identify major sections and portions of the application, including the user roles. 

***Task Goal:*** Gain a better understanding of the application for later analysis.

#### 7.1.3 Process Flow Modeling

***Level of Effort:*** Low

***Task Description:*** Model the process flows that users must follow while using the application. Identify dependencies between actions and requirements to get to each portion of the application.

***Task Goal:*** Gain a better understanding of the application for later analysis.

#### 7.1.4 Request/Resource Mapping 

***Level of Effort:*** Low 

***Task Description:*** Attempt to map, execute, and record every possible request in the application. Examine the requests and responses to understand how the application works from the developer’s perspective. Identify parameter names and values that are reflected back to the user or appear to be used in a database query. 

***Task Goal:*** Identify requests that have a higher probability of containing vulnerabilities. Prioritize for later analysis.

### 7.2 Application Discovery
This subcategory of penetration tasks focuses on the identification of vulnerabilities in the user interfaces or web services.


Figure 7.2a: Application Discovery Task Flow

#### 7.2.1 Default Configuration Testing

***Level of Effort:*** Low

***Task Description:*** Test the platform and application server configuration, such as SSL/TLS testing, file extension handling, method handling, and the existence of administrative interface and unreferenced links.

***Task Goal:*** Identify vulnerabilities in the application.

#### 7.2.2 Authentication Testing

***Level of Effort:*** Low

***Task Description:*** Test the application authentication for flaws such as user enumeration, guessable passwords, authentication bypass, flawed password reset, race conditions, multifactor authentication, and CAPTCHA implementation weaknesses.

***Task Goal:*** Identify vulnerabilities in the application.

#### 7.2.3 Session Management Testing 

***Level of Effort:*** Low

***Task Description:*** Test the application for session management flaws such as session fixation, session hijacking, unprotected session keys, and Cross Site Request Forgery (CSRF). 

***Task Goal:*** Identify vulnerabilities in the application.

#### 7.2.4 Authorization Testing

***Level of Effort:*** Low

***Task Description:*** Test the application for authorization flaws such as path traversal, authorization bypass, and privilege escalation.

***Task Goal:*** Identify vulnerabilities in the application.

#### 7.2.5 Business Logic Testing 

***Level of Effort:*** Low

***Task Description:*** Test the business logic flow and user process flow to verify steps that cannot be skipped or re-ordered. 

***Task Goal:*** Identify vulnerabilities in the application.

#### 7.2.6 Code Injection Testing

**Level of Effort:** Low

**Task Description:** Test the application for data validation flaws such as XSS, SQL Injection, LDAP injection, XPath Injection, overflows, format string issues, and HTTP Splitting.

**Task Goal:** Identify vulnerabilities in the application.

#### 7.2.7 Denial of Service Testing

**Level of Effort:** Low

**Task Description:** Test the application for flaws that may cause denial of service vulnerabilities either on the service platform, in the application logic, or on the backend systems and databases.

***Task Goal:*** Identify vulnerabilities in the application.

##### 7.2.8 Client-Side Code Testing

***Level of Effort:*** Low

***Task Description:*** Test the application for flaws in the use of mobile or client-side code.

***Task Goal:*** Identify vulnerabilities in the application.

### 7.3 Application Exploitation
This subset of penetration tasks focuses on the exploitation of vulnerabilities found in the previous tasks and the escalation of access the tester has in the application.

Figure 7.3a: Application Exploitation Task Flow

#### 7.3.1 Identify Attack Avenues 

**Level of Effort:** Medium 

**Task Description:** Review all findings and outputs from previous tasks and identify plausible attacks that have a moderate chance of success. Prioritize these possible attacks by likelihood and the tester’s ability to execute them.

***Task Goal:*** Organize and plan next steps.

#### 7.3.2 Vulnerability Exploitation 

***Level of Effort:*** Low to Medium 

***Task Description:*** Create proof of concept attacks to demonstrate the feasibility and business risk created by the discovered vulnerabilities. Once a vulnerability has been exploited, attempt to pivot and identify additional vulnerabilities to exploit. 

***Task Goal:*** Validate the assumed business risks created by the identified vulnerabilities and identify additional targets of opportunity.

#### 7.3.3 Post Exploitation

***Level of Effort:*** Low to Medium

***Task Description:*** Remove any code, data, or configurations that were added to the system as a part of the assessment.

***Task Goal:*** Return systems to their pre-assessment state.


</div>
