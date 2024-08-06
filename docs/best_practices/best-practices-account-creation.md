---
layout: default
title: Account creation
nav_order: 10
parent: Best practices
---

# Account creation
{: .fs-9 }

PLACEHOLDER
{: .fs-6 .fw-300 }


---

## Collecting Personal Information during Account Creation 

Simplifying account creation by not reducing the collection of required personal information, can speed up application submission time, reduce administrative burden, reduce risk of exposing applicant data, and help maintain security and privacy. FNS only requires the collection of name, address, and signature of the applicant applying for SNAP. 

---
![Account creation](/assets/images/best-practices/account-creation/account-creation.png){:.image-popout-vert}

---
### Annotations

1. The personal information that is collected during account creation may vary per state policies and regulations. Collecting certain types of PII like first name and last name enables the addition of those fields to a prohibited password list.


---
### Examples from states

These state SNAP applications offer a digital path to apply with only name, address, and signature: [California](https://www.getcalfresh.org/en/apply), [Michigan](https://newmibridges.michigan.gov/s/isd-external-afb-screen?language=en_US), [Nebraska](https://iserve.nebraska.gov/apply/start), [Kentucky](https://kynect.ky.gov/benefits/s/getstartedsnap?language=en_US), and [Washington](https://www.washingtonconnection.org/eapplication/home.go). 

These state Medicaid applications offer an option to submit an application without creating an account: [Michigan](https://newmibridges.michigan.gov/s/isd-external-afb-screen?language=en_US) and [Nebraska](https://iserve.nebraska.gov/apply/start).
 
For visual examples, see Appendix Item A: Examples from States. 


---
### Policy best practices

<details>
	<summary>FNS</summary>
	<ul>
		<li>
			<p class="req">Personal information, such as name, DOB, phone number, and home address are not required for setting up the account. The only parts that are required are username and password.</p>
			<p class="req-source"><a href="https://fns-prod.azureedge.us/sites/default/files/snap/Best-Practices-for-Online-SNAP-Applications.pdf">Source: SNAP Guidance Best Practices for Online Applications - 4.1</a></p>
		</li>
		<li>
			<p class="req">Does the registration provide a simple system (just a few steps) allowing users to set up usernames, application numbers, and/or passwords? (Required) Recommendation includes: — Do not require a social security number to register.</p>
			<p class="req-source"><a href="https://fns-prod.azureedge.us/sites/default/files/snap/Best-Practices-for-Online-SNAP-Applications.pdf">Source: SNAP Guidance Best Practices for Online Applications - 8.7</a></p>
		</li>
	</ul>
</details>

---
### Policy requirements

<details>
	<summary>FNS</summary>
	<ul>
		<li>
			<p class="req">7 CFR 273.2 (b)(1)(v); 273.2(n)(1)(v) In plain and prominent language on or near the front page of the application, notification of the household's right to immediately file the application as long as it contains the applicant's name and address and the signature of a responsible household member or the household's authorized representative. Regardless of the type of system the State agency uses (paper or electronic), it must provide a means for households to immediately begin the application process with name, address and signature...<br/>
			<br/>
			Federal law provides applicants with the right to file a SNAP application providing only name, address, and signature. Therefore, state agencies must accept and establish a filing date for any SNAP application that includes a name, address, and signature, even if other questions on the application form are incomplete. State agencies must consider such applications as “filed” and provide benefits from the filing date for eligible households. For online applications, this means that state agencies can encourage but cannot require applicants to complete any additional fields in order to advance through and/or file/submit the application. The online application must include the name, address, and signature fields on one of its initial screens, and questions other than name, address, and signature must be optional. One option to meet this requirement is by including a “submit now” button immediately following the name, address, and signature fields. State agencies should also consider including a “submit” button on every screen or at frequent points as the applicant advances through the online application to prevent applicants from having to advance through every screen to submit.<br />
			<br/>
			These requirements apply to all types of SNAP applications, including multiprogram applications, paper applications, or mobile applications and apply regardless of other means of applying (such as the availability of paper applications). For example, a state is not permitted to require additional information on its online application based on the reasoning that households not wanting to provide more than name address and signature can apply via paper.
			</p>
			<p class="req-source"><a href="https://www.fns.usda.gov/snap/online-application-policy-clarification">Source: Online Application Policy Clarification (FNS, 2024)</a></p>
		</li>
	</ul>
</details>

<details>
	<summary>NIST</summary>
	<ul>
		<li>
			<p class="req">Agencies SHALL select a minimum of AAL2 when self-asserted PII or other personal information is made available online. </p>
			<p class="req-source"><a href="https://pages.nist.gov/800-63-3/sp800-63b.html#4-authenticator-assurance-levels">Source: NIST Special Publication 800-63B, 4 Authenticator Assurance Levels</a></p>
		</li>
		<li>
			<p class="req">While a CSP MAY bind an AAL1 authenticator to an IAL2 identity, if the subscriber is authenticated at AAL1, the CSP SHALL NOT expose personal information, even if self-asserted, to the subscriber.</p>
			<p class="req-source"><a href="https://pages.nist.gov/800-63-3/sp800-63b.html#611-binding-at-enrollment">Source: NIST Special Publication 800-63B, 6.1.1 Binding at enrollment</a></p>
		</li>
		<li>
			<p class="req">Any PII or other personal information — whether self-asserted or validated — requires multi-factor authentication. Therefore, agencies SHALL select a minimum of AAL2 when self-asserted PII or other personal information is made available online.</p>
			<p class="req-source"><a href="https://pages.nist.gov/800-63-3/sp800-63b.html#4-authenticator-assurance-levels">Source: NIST Special Publication 800-63B, 4 Authenticator Assurance Levels</a></p>
		</li>
	</ul>
</details>