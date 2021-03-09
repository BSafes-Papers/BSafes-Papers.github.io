---
layout: default
title: INTRODUCTION
parent: § Internet Architecture and Disability 
grand_parent: Internet
nav_order: 10
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

## INTRODUCTION
The nearly fifty-million Americans who are deaf or hard of hearing, many of whom have speech disabilities, face limited outlets for real-time communication, a glut of Internet-delivered video programming with missing or poor-quality captions, and an increasingly large array of devices with inaccessible voice-operated interfaces.<sup>1</sup>  The more than seven million Americans who are blind or visually impaired have witnessed the revolution of web and mobile applications pass with inconsistent, broken, or missing support for screen readers and a dearth of video content with audio descriptions.<sup>2</sup>  The estimated two-and-a-half million to nearly twelve-million Americans with intellectual and cognitive disabilities routinely face complex user interfaces designed without considering cognitive load and a dearth of content delivered in plain language.<sup>3</sup> And millions more have motor and physical disabilities that prevent them from interacting with a variety of Internet-enabled devices and applications, including the “smart” vehicles, homes, and clothing that constitute the “Internet of Things.” Making the Internet accessible to people with disabilities is one of the most pressing civil rights challenges of the twenty-first century, with unique and complex legal, technical, architectural, and political dimensions.

More generally, the United Nations estimates that a billion people—fifteen percent of the world’s population—live with a disability, making people with disabilities “the world’s largest minority.”<sup>4</sup> Yet the Internet—the gateway to the economic, social, cultural, and participatory fruits of the information age—has remained inaccessible,<sup>5</sup>  in a variety of ways, to this significant population.

These are not trivial concerns of luxury or convenience. People with disabilities have faced historical barriers to societal institutions that are, in many cases, exacerbated by Internet-enabled technological disruptions that render social change without accessibility in mind. Access to the Internet is a primary driver of education, employment, civic participation, cultural engagement, and more. The denial of equal access to the Internet is tantamount to “second-class citizenship” and inhibits the social integration mandate of the ADA.<sup>6</sup>  The Internet likewise promises to serve the ADA’s integration mandate as much or more than any other technological development, and “promotes democratic engagement and human fulfillment by fostering understanding and communication among people with and without disabilities across the economic spectrum.”<sup>7</sup>  Against this backdrop, shortcomings in Internet accessibility threaten to deny millions of Americans access to the economic, educational, cultural, and democratic life of the twenty-first century.<sup>8</sup>

***
<sup>1</sup>. Frank R. Lin, John K. Niparko & Luigi Ferrucci,* Hearing Loss Prevalence in the United States*, 171 ARCHIVES INTERNAL MED. 1851, 1851–52 (2011).
{: .fs-2}
<sup>2</sup>. *See Blindness Statistics*, NAT’L FED’N OF THE BLIND, https://nfb.org/blindness-statistics [https://perma.cc/53TV-LN9N].
{: .fs-2}
<sup>3</sup>. *See* THE NAT’L ACADS. OF SCI. ENG’G MED., MENTAL DISORDERS AND DISABILITIES AMONG LOW-INCOME CHILDREN 267–79 (Thomas F. Boat & Joel T. Wu eds., 2015) (ebook).
{: .fs-2}
<sup>4</sup>. Dep’t of Econ. and Soc. Affairs, *Factsheet on Persons with Disabilities,* UNITED NATIONS, https://www.un.org/development/desa/disabilities/resources/factsheet-on-persons-with-disabilities.html [https://perma.cc/DE4A-WX8P].
{: .fs-2}
<sup>5</sup>. See PETER BLANCK, EQUALITY: THE STRUGGLE FOR WEB ACCESSIBILITY BY PERSONS WITH COGNITIVE DISABILITIES 45–49 (2014).
{: .fs-2}
<sup>6</sup>. JONATHAN LAZAR, DANIEL GOLDSTEIN & ANNE TAYLOR, ENSURING DIGITAL ACCESSIBILITY THROUGH PROCESS AND POLICY 91 (2015).
{: .fs-2}
<sup>7</sup>. BLANCK, *supra* note 5, at 40, 44.
{: .fs-2}
<sup>8</sup>. *See* Bradley Allan Areheart & Michael Ashley Stein, *Integrating the Internet,* 83 GEO. WASH. L. REV. 449, 452 (2015).
{: .fs-2}
***

This Article starts from the premise that full access<sup>9</sup> to the Internet for people with disabilities<sup>10</sup> is normatively important and that to achieve Internet accessibility for people with disabilities, “anti-discrimination measures and positive actions are sometimes needed.”<sup>11</sup> While many anti-discrimination movements begin with a fight to overcome overt animus, the movement toward Internet accessibility has, from its inception, dealt more directly with questions of how to overcome omissive failures to incorporate accessibility into the design of technological systems by the proprietors, vendors, and users of Internet-enabled technology.<sup>12</sup>

In other words, Internet accessibility is situated squarely in what Samuel Bagenstos has deemed in the context of employment law a “structural turn” in the broader movement to fight discrimination against people with disabilities.<sup>13</sup> The questions Internet accessibility poses are not matters of preventing conscious animus toward people with disabilities, but matters of constructing and remediating architecture and content to make it accessible and usable; the answers are not merely barring discriminatory conduct, but identifying specifically who must do what, and when, and how, to ensure that people with disabilities can fully use the Internet. These questions and answers are no less important from the perspective of antidiscrimination theory than those of animus,<sup>14</sup> but they require a structural set of doctrinal accessibility mandates to fulfill the normative vision of antidiscrimination.<sup>15</sup>

***
<sup>9</sup>. The term “equal access” is often used as well, though it elides that accessibility often entails customization tailored to the particular aspects of a person’s disability.
{: .fs-2}
<sup>10</sup>. This Article uses “person-first” language—e.g., “people with disabilities” throughout primarily as a matter of consistency, and not as an intentional endorsement of person-first language over identity-first language—e.g., “disabled people.”—or an attempt to stake a position in the debate over the appropriate language to use. While I interact with many accessibility advocates in my clinical work who prefer “person-first” language, others prefer identity-first language. *See, e.g*., Lydia X. Z. Brown, *The Significance of Semantics: PersonFirst Language: Why It Matters *(Aug. 4, 2011), https://www.autistichoya.com/2011/08/ significance-of-semantics-person-first.html [https://perma.cc/KX6C-69PT] (arguing for the use of identity-first language). Also, this Article does not contend in depth with the debate over the scope of disabilities that should be swept into the right to equal access. *See infra* Section III.E.
{: .fs-2}
<sup>11</sup>. BLANCK, *supra* note 5, at 45.
{: .fs-2}
<sup>12</sup>. This is not to suggest that the accessibility requirements on the Internet have been or will be uncontroversial. For example, Eric Goldman has argued that applying the ADA to the Internet will “potentially rip[] open a huge hole in Internet law” and enable “jobless recent law school grads” to make “buckets of money . . . in ADA litigation against Internet companies.” Eric Goldman, *Will the Americans With Disabilities Act Tear a Hole in Internet Law?*, ARS TECHNICA (June 27, 2012, 9:30 AM), https://arstechnica.com/tech-policy/2012/06/will-the-americans-with-disabilities-act-tear-a-hole-in-internet-law/ [https://perma.cc/72LC-GRHE]. Though grappling with the treatment of disability issues by Internet law scholars is beyond the scope of this Article, some of the economic concerns that Goldman and others raise are addressed in the context of this Article’s discussion on undue economic burden. *See supra* Section III.C.
{: .fs-2}
<sup>13</sup>. *See generally* Samuel R. Bagenstos, *The Structural Turn and the Limits of Antidiscrimination Law*, 94 CALIF. L. REV. 1 (2006) (discussing proposals for structural approaches to employment discrimination law).
{: .fs-2}
***

This Article aims to grapple, then, with the question of how, exactly, the goal of Internet accessibility can be achieved, and provide disability-law scholars and advocates with a lens for more comprehensively understanding that set of problems that “Internet accessibility,” broadly construed, should be concerned with solving.

Part I of this Article observes that the use of Title III of the ADA as the wellspring for Internet accessibility has led to a prevailing doctrinal approach to Internet accessibility that is rooted in a place-centric conception of the civil rights of people with disabilities. This approach advocates treating the Internet as a metaphorical“place” subject to Title III of the ADA, which requires places of public accommodations to be accessible to people with disabilities.16 As a result, much of the attention to Internet accessibility is centered on Internet-enabled technology that is easily amenable to Title III’s “place” metaphor. The technology most amenable to that metaphor is the websites that comprise the World Wide Web (colloquially, “the web”), which users “visit” or “go to” using their computer’s web browser. In disability scholarship, *Internet* accessibility has become implicitly synonymous with *web* accessibility.

Part II introduces the Internet-law literature of “perspectives” to Internet accessibility. Applying the perspectives literature reveals that the prevailing place-and website-centric approach to Title III is properly understood as what Internet-law scholars call an “internal” perspective, rooted in the user’s experience of the Internet. While I explain why such a perspective is both doctrinally and normatively justified, I also describe the shortcomings of the internal perspective as a framework for addressing Internet accessibility beyond the application of Title III to websites. By augmenting the internal perspective on Title III with a countervailing “external” perspective, I sketch a broader framework for addressing Internet accessibility informed not only by the experience of using the Internet, but by the Internet’s layered architecture.

***
<sup>14</sup>. *See, e.g*., Samuel R. Bagenstos, “*Rational Discrimination,” Accommodation, and the Politics of (Disability) Civil Rights*, 89 VA. L.REV. 825, 826–27 (2003) (rejecting a “normative distinction between the [ADA]’s mandate to provide ‘reasonable accommodation’ to people with disabilities and the antidiscrimination requirements of the civil rights laws that emerged in the 1960s and 1970s”); *see also* Helen Norton, *The Supreme Court’s Post-Racial Turn Towards a Zero-Sum Understanding of Equality,* 52 WM. & MARY L. REV. 197, 206 (2010) (discussing “whether antidiscrimination law should be understood as driven by antisubordination as opposed to anticlassification values”).
{: .fs-2}
<sup>15</sup>. Sarah Schindler has addressed issues of discrimination and exclusion in physical, built architecture. *See* Sarah B. Schindler, *Architectural Exclusion: Discrimination and Segregation Through Physical Design of the Built Environment*, 124 YALE L.J. 1934 (2015).
{: .fs-2}
<sup>16</sup>. 42 U.S.C. § 12182(a) (2012). Place-centrism is uncommon in disability laws outside of Title III of the ADA; Title I focuses on employment, 42 U.S.C. ch. 126, subch. I (2012); Title II focuses on state and local government services, 42 U.S.C. ch. 126, subch. II (2012); and Title IV focuses on telecommunications relay services, 47 U.S.C. § 225 (2012). Sections 504 and 508 of the Rehabilitation Act of 1976, 29 U.S.C. §§ 794, 794(d) (2012), and state laws such as California’s Unruh Civil Rights Act, CAL. CIV. CODE § 51 (West 2007) and Disabled Persons Act, CAL. CIV. CODE §§ 54–55.2 (West 2007), have different substantive scopes that do not necessarily focus on places. Though a full exploration of these laws is beyond the scope of this article, these laws potentially play an important role in Internet accessibility. *See infra* Sections III.C, III.D, and III.E.
{: .fs-2}
***

In Part III, I color in the external sketch by illustrating with examples what a more comprehensive realization of the goal of Internet accessibility would require. I first disentangle the application and content layers of both the web and the diverse array of modern Internet applications, including those delivered by dominant platform companies that host the content of their users. I close with a discussion of underexplored accessibility considerations specific to the Internet’s building blocks—the network and physical layers—and the class of devices that comprise the so-called “Internet of Things,” in which issues such as the accessibility dimensions of network neutrality and voice assistants arise. Throughout, I consider the role that other substantive bodies of law—in particular, telecommunications law—may play in facilitating a more comprehensive approach to Internet accessibility.

</div>
