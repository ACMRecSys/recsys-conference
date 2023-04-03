# RecSys 2023 - Guide to Reviewing Papers[^1]
Tommaso Di Noia & Min Zhang - RecSys 2023 Program Chairs

## Reviewing Process and Roles

Each paper will be assigned to three reviewers and one meta-reviewer.
- **Reviewers**.  Each reviewer is assigned to write an independent review of the paper.  In general, reviewers will include three members of the program committee matched to the paper based on their expertise.
- **Meta-reviewers**.  The meta-reviewer for a paper is assigned to coordinate the paper’s reviews, facilitate discussion among the reviewers, write a meta-review that summarizes the consensus of the reviews (and may highlight points where there is no consensus), and makes a recommendation to the program chairs on acceptance or rejection of the paper.  

Reviews and meta-reviews will be visible to the authors when decisions are made and announced.

## Scope
Your primary consideration when evaluating a paper should be whether it provides a strong and original contribution to the field of Recommender Systems. Ricci, Rokach, and Shapira described Recommenders Systems as “software tools and techniques that provide suggestions for items that are most likely of interest to a particular user” (Recommender Systems Handbook, 2nd Ed., p. 1). Such tools and techniques include models of user preference, item characteristics, and user-item affinitities; algorithms for predicting user preference or selecting items likely to be of interest to users; interfaces for eliciting preferences or providing recommendations; studies and metrics related to the value and aspects of recommendation; and systems that apply these tools and techniques to different domains.  We encourage a wide variety of contributions to RecSys, ranging from theoretical contributions to practical demonstrations of working systems.

Papers may be considered out-of-scope if they do not clearly argue this contribution. For example, a paper suggesting theoretical improvements to matrix factorization algorithms should be backed by experiments that clearly demonstrate effectiveness in recommendation scenarios.  A paper presenting a new interface for displaying a set of songs should include design and evaluation showing how that interface affects recommender systems for songs specifically.  Similarly, a presentation of a deployed system should present reusable findings, methods or artifacts that will benefit researchers in the community and designers of other systems. Contributions that do not make a generalizable research contribution backed by evidence may be more suited to the demonstrations or late-breaking results tracks.


## Desk Rejection Criteria
Reviewers are invited to flag papers that they believe may be candidates for desk rejection (i.e., rejection without full review). Reviewers should communicate such issues to the paper’s meta-reviewer, who will advise as to whether a full review is required. Criteria for desk rejection include:
Papers that are outside the conference scope, that are incomplete, or that fail to claim a contribution to the field, present evidence, or discuss the prior work relevant to their contribution.  
Papers that violate formatting guidelines, in particular those that exceed the page limit.
Papers that do not describe original work or are under review elsewhere (including as another paper submission for RecSys); note that papers previously published in workshop proceedings may be submitted to RecSys only if the submission includes at least 30% new content.
Papers that are not properly anonymized to enable mutually anonymous review.  
Papers that are found to include plagiarized content.  

## Mutually Anonymous Review
RecSys reviewing is mutually anonymous (double-blind).  Authors do not know the identity of their reviewers, and reviewers do not know the identity of the authors. The responsibility for double-blind review is a shared one between authors and reviewers:

Authors must not identify themselves in the papers.  No names or affiliations should appear on the paper.  References to identifying institutions should be obscured (e.g., instead of “We carried out this study in Ebay” the authors could write “We carried out this study in an online auction site” -- that can be re-identified after review if the paper is accepted).  If referring to and building on an author’s own prior work, the work can be referred to in the third person, or anonymized, whichever seems most appropriate. (E.g., “We carried out this study in our XXX system (anonymized)” or “We build upon Kim’s taxonomy of recommender tasks” (without noting that we include Kim on our team)).  Authors should also not take steps specifically to make their authorship of the paper known.  For example, you should not put out an announcement (in a venue that RecSys reviewers would likely read) that “I just submitted ‘a new linear approach to matrix factorization using quantum Eigenfactors’ to ACM RecSys -- wish me luck!” 

RecSys does support open science.  Authors who wish to deposit preprints of their work on sites such as arXiv or in technical report archives are allowed to do so.
 
Reviewers are expected to avoid attempts to seek the authors of work.  Do not search for the work online.  Do not contact specific authors to find out if this is their work.  If you routinely follow lists of arXiv deposits or tech report updates, you may wish to delay reading those during the period when you are reviewing.  If in reading a work you feel that you likely have a conflict of interest with the author (e.g., one of us once recognized the writing style of one of our former graduate students -- even though we didn’t know of the work), please contact your meta-reviewer or the program chairs to voice your concern.  If there is a conflict, we can re-assign you to another paper.  

## Plagiarism
Plagiarized papers will not be accepted for RecSys 2022. We will be checking the plagiarism level of all submitted papers to ensure content originality using an automated tool.  Automated tools, however, have limitations.  If you suspect plagiarism in a submission you are reviewing, please let us know (an email to program2022@recsys.acm.org with the details would be helpful).  

## Replicability
Replicability is a critical component of recommender systems research. Replicability is to be assessed in the context of the work itself — we recognize that a set of customer interviews (for example) may not be shareable, but the interview scripts can be provided, along with response coding protocols. Sharing of data sets and code is encouraged, and authors presenting work that was tested on proprietary data may wish to include a secondary analysis on a public or shareable data set.

As such we ask reviewers to carefully consider replicability in the specific context of the work they’re reviewing. For instance, in cases where authors make use of proprietary data, do they also report results on public data that would allow comparison? If source code will not be released, is the standard of presentation in the paper sufficient that a knowledgeable reader could reproduce the main results? If the results or methods are only applicable industrial settings (e.g. they rely on very large social network graphs), are they described in sufficient detail that a scientist at a different company with similar resources could reproduce them?

## Ethical Considerations
ACM RecSys expects all authors to comply with ethical and regulatory guidelines associated with human subjects research, including research involving human participants and research using personally identifiable data. Papers reporting on such human subjects research must include a statement identifying any regulatory review the research is subject to (and identifying the form of approval provided), or explaining the lack of required review. Note that requirements vary from country to country (and in some cases within countries).  Reviewers are asked to consider whether the research was conducted in compliance with applicable ethical and regulatory guidelines.  

As stated in the CfP, papers that include text generated from a large-scale language model (LLM) such as ChatGPT are prohibited unless this produced text is presented as a part of the paper’s experimental analysis. The same holds for reviewers. AI tools may be used to edit and polish reviewers’work, but text "produced entirely" by AI should be avoided. 


We encourage authors to consider further ethical implications and broader impacts of their work, and to discuss these in an appropriate section of their papers. Reviewers should consider the clarity and justification for these claims. 




[^1]: These guidelines are partly based on the [CHI 2020 reviewer guide](https://chi2020.acm.org/guide-to-reviewing-papers/).  
