# Guide for submitting to RO2019
{:.no_toc}

This page describes how authors could submit to the [Workshop on Research Objects (RO2019)](http://www.researchobject.org/ro2019/).

> tl;dr: Preprint (and additional resources) should be uploaded to the [RO Zenodo community](https://zenodo.org/deposit/new?c=ro).
>
> The Zenodo research object is submitted for review in [EasyChair](https://easychair.org/conferences/?conf=ro2019) or [GitHub](https://github.com/ResearchObject/ro2019/issues/new/choose)
> 
> Upon acceptance, the RO2019 proceedings will link to Green Open Access preprints/ROs in Zenodo, and DOI to papers accepted for the IEEE eScience proceedings.

* Table of Contents
{:toc}

## Submission types

RO2019 welcomed submissions for:

### Oral Communications

* **Short articles**: (about 4-8 pages) for more developed research, software or data contributions 
* **Abstracts**: (1-2 pages) for oral communication
* **Poster and demo abstracts**: (1-2 pages)

The page limits are for guidance only, assuming reasonable font sizes and margins.

See the [Call for Papers](cfp) for details on topics covered at the workshop.

For any questions, email the RO2019 Workshop Organizers at [ro2019@easychair.org](mailto:ro2019@easychair.org)

### Unconference

Workshop participants are also encouraged to separately propose _lighting talks_, _breakout sessions_ and ideas for discussion points for the _unconference_ session of the workshop. To suggest an unconference activity, please [raise an issue](https://github.com/ResearchObject/ro2019/issues) in GitHub.

## Requirements

Unless indicated otherwise, the submitted preprint is assumed to be licensed [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/), and will, upon acceptance, be made available as **Green Open Access** on the [RO2019 website](http://www.researchobject.org/ro2019/) with DOI links to the Zenodo record and (where applicable) DOI for the published IEEE eScience Proceedings article.

RO2019 may reformat your preprint for web publishing.

It is a requirement that **at least one author** of each accepted submission attends the RO2019 workshop and **registers** using the [IEEE eScience 2019 system](https://escience2019.sdsc.edu/registration) (either for the workshop, or the whole conference). Registration [fees](https://escience2019.sdsc.edu/registration) applies.


## Formats

Submitted abstracts and articles can be in a range of **open formats** (e.g. [HTML5](https://www.w3.org/TR/html/), [ePub](https://www.w3.org/Submission/2017/SUBM-epub31-20170125/)) and are particularly encouraged to be submitted in a FAIR research data packing format. Guidance is provided below for those who do not have their own platform they wish to showcase. 

Accepted articles will be included in the IEEE eScience 2019 proceedings; a secondary PDF, which may use the [IEEE templates](https://www.ieee.org/conferences/publishing/templates.html), **may** be included in the submission or provided later by the author to the IEEE submission system (camera-ready deadline for IEEE articles 29 July 2019).


## Submitting

Submissions should be uploaded to the [RO Zenodo community](https://zenodo.org/communities/ro/) and submitted for review in [EasyChair](https://easychair.org/conferences/?conf=ro2019).

You may also place your submission in another open repository and provide its permalink/DOI to EasyChair. Note that we will rely on the repository for later publishing of the preprints.

See guidance below for further details.


## Open Peer Review

RO2019 encourages _open peer review_, and recommend that reviewers are named and attributed; however reviewers may be anonymous if so desired. Reviewers are welcome to publish their reviews using the same guidelines as the research articles.

[Peer reviews](reviews) will be published on the RO2019 website following the workshop.

## Contact

For any questions, email the RO2019 Workshop Organizers at [ro2019@easychair.org](mailto:ro2019@easychair.org)


## Guidance

Below are detailed instructions on how we recommend submitting your work to RO2019:
	
* Author abstract/article
* Upload to Zenodo	
* Submit for review in Easychair (or GitHub)
* Update in Zenodo

### Authoring

Use any authoring tool you prefer, as long as you can output in an open format with hyperlinks (e.g. HTML). Here is a list of some options of web-aware authoring tools:

  * [Authorea](https://www.authorea.com/) - web-based collaborative system for authoring in Markdown, LaTeX and WYSIWIG.
  * [dokieli](https://dokie.li/) - web-based WYSIWYG editor with a range of annotation and rendering option. Requires a [personal storage](https://dokie.li/#personal-storage) account or server.
  * [Fidus Writer](https://www.fiduswriter.org/) - web-based academic writing environment
  * [Markdown](https://guides.github.com/features/mastering-markdown/) - textual HTML template language, rendered using [pandoc](https://pandoc.org/), [GitHub Pages](https://pages.github.com/) or [Jekyll](https://jekyllrb.com/)
  * [Scholarly Markdown](http://scholarlymarkdown.com/) - MarkDown [extensions for academic writing](http://scholarlymarkdown.com/Scholarly-Markdown-Guide.html#summary-of-new-features-in-scholarlymarkdown)
  * [RASH Javascript Editor(RAJE)](https://rash-framework.github.io/raje-app/) - Javascript-based word processor for creating RASH documents
  * [Scholarly HTML](https://w3c.github.io/scholarly-html/) - conventions for academic writing in HTML
  * [Stencila](https://github.com/stencila/stencila) - platform for creating, collaborating on, and sharing data driven content.

Save your article as HTML, which may require you to use a ZIP or ePub archive to contain associated figures and CSS. You may optionally publish the preprint article on a website of your choice, and provide a URL to this during submission together with a static PDF rendering.

#### Word processors

Below are some legacy tools that are perhaps better at producing PDFs than web documents. If you prefer any of these you may want to use a [IEEE template](https://www.ieee.org/conferences/publishing/templates.html) as starting point, then use [RASH Online Conversion Service (ROCS)](https://rash-framework.github.io/rocs.html) to convert to HTML:
	
  * [Overleaf](https://www.overleaf.com/) - write LaTeX collaboratively on the web and GitHub	
  * [Google Docs](https://www.google.com/docs/about/) - collaborative web-based word processor
  * [Apache OpenOffice](https://www.openoffice.org/) or [LibreOffice](https://www.libreoffice.org/) - traditional word processor	
  * [Microsoft Office](https://products.office.com/en-gb/word) locally or online with [Office 365](https://www.office.com/)

If you use a legacy tool it is recommended you upload both a PDF and HTML version of your article.

#### Example: Google Docs

After using a word processor like Google Docs from a [IEEE template](https://www.ieee.org/conferences/publishing/templates.html), Save/Download as **Web page (HTML, zipped)** as well as **PDF**:
[![gdoc-html](assets/img/gdoc-html.png)](assets/img/gdoc-html.png)

### Zenodo

RO2019 promotes [Open Research](https://en.wikipedia.org/wiki/Open_research), and encourage authors to upload their Open Access preprint and resources to an open repository like [Zenodo](http://about.zenodo.org/), an Open Data repository provided by CERN and supported by [OpenAIRE](https://www.openaire.eu/).

Perhaps the simplest (lower-case) "research object" is a [Zenodo](https://zenodo.org/) record that contains:
	
* Abstract/article as HTML
* Abstract/article as PDF

If you are new to Zenodo you can play with the separate [sandbox instance](https://sandbox.zenodo.org/) first, where we have provided an equivalent [sandbox RO community](https://sandbox.zenodo.org/communities/ro/). Note that RO2019 submissions must use the [main Zenodo](http://zenodo.org/) instead of the sandbox.

Most of the information in the Zenodo form is optional, for RO2019 it is recommended you fill in these fields:
	
  * **Type:** Conference
  * **Author:** Your Full Name (_in your_ _[preferred order](https://www.w3.org/International/questions/qa-personal-names)_)
  * **ORCID:** (your [ORCID ](https://orcid.org/) identifier)
  * **Title:** (_same as in article_)
  * **Additional notes:** Preprint submitted to RO2019 workshop at IEEE eScience Conference 2019
  * **License:** Open Access  (_Note: This is the license of the preprint_)
  * **Abstract:** (_same as in article, unless the upload is an academic abstract_)

You may also want to fill in **Related Identifiers**, in particular if your submission already have a web-version, or has related datasets, software or websites. You do not need to fill in _References_.


### Example: Uploading to Zenodo


If you have not already done so, [sign up for Zenodo](https://zenodo.org/signup/). We recommended to use your [ORCID](https://orcid.org/) account to simplify registration and login.

Then, from the [Research Object Community](https://zenodo.org/communities/ro/) page in Zenodo, click [Upload](https://zenodo.org/deposit/new?c=ro) to add a new submission.
[![Upload to Zenodo](assets/img/zenodo-00-ro-upload.png)](assets/img/zenodo-00-ro-upload.png)

Now upload both the HTML and PDF version of your article:
[![zenodo-02-upload](assets/img/zenodo-02-upload.png)](assets/img/zenodo-02-upload.png)

It is recommended to also upload (or link) to related resources that support your work. Examples:
	
  * [Research Objects](http://www.researchobject.org/specifications/) (e.g. [RO Bundle](https://w3id.org/bundle/), [BagIt](https://w3id.org/ro/bagit), [BDBag](http://bd2k.ini.usc.edu/tools/bdbag/))
  * FAIR [Research Data Package](https://rd-alliance.org/approaches-research-data-packaging-rda-11th-plenary-bof-meeting) (e.g. [science.ai](https://nightly.science.ai/documentation/archive) package, [DataOne package](https://releases.dataone.org/online/api-documentation-v2.0.1/design/DataPackage.html), [DataCrate](https://github.com/UTS-eResearch/datacrate/blob/master/spec/1.0/data_crate_specification_v1.0.md), [FrictionLess Data package](http://frictionlessdata.io/data-packages/))
  * [Figures](https://figshare.com/)
  * [Datasets](https://www.datacite.org/)
  * [Software](https://research-software.org/citation/)
  * [Scripts](https://gist.github.com/)	
  * [Workflows](https://www.myexperiment.org/)
  * [R](https://bookdown.org/yihui/rmarkdown/notebook.html) or [Jupyter](http://jupyter.org/) Notebooks
  * [Provenance](https://www.w3.org/TR/prov-overview/) and logs

However if these are already available in existing repositories (e.g. [Zenodo](https://zenodo.org/), [Figshare](https://figshare.com/)) you should instead refer to them by DOI or URL under **Related Identifiers** further down.

Remember to click the **Start Upload** button:

![Start Upload](assets/img/zenodo-09-start-upload.png)

At any point you can click the **Save** button to store the draft (upload and metadata) under your [Zenodo uploads](https://zenodo.org/deposit).

[![Save](assets/img/zenodo-10-save-then-publish.png)](assets/img/zenodo-10-save-then-publish.png)

Now fill in **Publication Type** (Conference), **Title** and **Authors**.
Leave _DOI_ blank. (After acceptance you may create a _New Version_ of this Zenodo record and provide the published DOI from the IEEE proceedings).

[![zenodo-03-info](assets/img/zenodo-03-info.png)](assets/img/zenodo-03-info.png)

If the submission is an article, provide the article's abstract as **Description**. (For academic abstracts you may leave this field blank or provide your own shorter abstract)

Under **Additional Notes** make it clear that this is a Preprint. Suggested text is:
> Preprint submitted to RO2019 workshop at IEEE eScience Conference 2019
[![zenodo-04-notes-and-license](assets/img/zenodo-04-notes-and-license.png)](assets/img/zenodo-04-notes-and-license.png)

If you prefer a different Open Access license for your preprint, select one here. Note that the IEEE eScience Conference proceedings are unfortunately not open access, which is why we rely on the Zenodo uploads to make your accepted work available.

If you have received funding for your research, e.g. from [H2020](https://ec.europa.eu/programmes/horizon2020/), then you may indicate this under **Funding**:
[![zenodo-06-funding](assets/img/zenodo-06-funding.png)](assets/img/zenodo-06-funding.png)

If you have a web version of your submission, a website or webapp, or any related resources in other repositories that you would like to link to by DOI or URL, then add them under **Related Identifiers**:
[![zenodo-07-related-identifiers](assets/img/zenodo-07-related-identifiers.png)](assets/img/zenodo-07-related-identifiers.png)

Finally, click Save followed by Publish:
[![Save](assets/img/zenodo-10-save-then-publish.png)](assets/img/zenodo-10-save-then-publish.png)

You will need to confirm that your upload is final:
[![zenodo-12-confirm](assets/img/zenodo-12-confirm.png)](assets/img/zenodo-12-confirm.png)

Now your preprint is uploaded to Zenodo:
[![zenodo-12-ready](assets/img/zenodo-12-ready.png)](assets/img/zenodo-12-ready.png)

Copy the **DOI** or URL of the Zenodo Record, e.g. [https://sandbox.zenodo.org/record/214634](https://sandbox.zenodo.org/record/214634), as you will need it in the EasyChair submission for RO2019 peer review next.


### Submit for review in EasyChair

After creating a Zenodo record (see above), you will need to submit it to RO2019 for review using [EasyChair](https://easychair.org/). You will need to [signup to EasyChair](https://easychair.org/account/signup.cgi) if you do not already have an account.

From the [RO2019 EasyChair submission page](https://easychair.org/conferences/?conf=2019), click **Enter as an Author**.

Add Corresponding **Author** to EasyChair. As you will be submitting your Zenodo record, you are **not** required to add co-authors again in EasyChair, unless _Corresponding Author_ is different from _Speaker_ or yourself.
[![easychair-01-author](assets/img/easychair-01-author.png)](assets/img/easychair-01-author.png)

In the EasyChair **Abstract** field, you do **not** need to duplicate the abstract from Zenodo. Simply paste the **URL to the Zenodo record** or the permalink to your submission in another open repository.
[![easychair-03-no-abstract](assets/img/easychair-03-no-abstract.png)](assets/img/easychair-03-no-abstract.png)
_Note: If you do not provide a Zenodo record URL in the abstract, you MUST upload a PDF to EasyChair._

Select the **Category** of your submission type:
[![easychair-04-category](assets/img/easychair-04-category.png)](assets/img/easychair-04-category.png)

If you created a PDF you may optionally also click **Browse** to upload it to EasyChair. The submitted preprint is assumed to be licensed [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/) unless stated otherwise.

Finally **submit** your contribution for consideration:
[![easychair-05-submit](assets/img/easychair-05-submit.png)](assets/img/easychair-05-submit.png)

EasyChair should send you a confirmation email, and will send you more emails during the review process.


### Alternative: Submit for review in GitHub

As an alternative to EasyChair, this year we also support submission of abstracts and article through GitHub. Submitting by GitHub means peer review will be done in public from day 1. If you prefer peer review to not open until acceptance, instead submit by EasyChair, as described above.

RO2019 GitHub submission procedure:

1. Sign up to or log in at <https://github.com/>
2. Create a new issue at <https://github.com/researchobject/ro2019/issues> - selecting the appropriate submission type
3. For articles and longer abstracts, provide DOI for preprint uploaded at <https://zenodo.org/deposit/new?c=ro>
4. For short abstracts and demo/poster submission you can instead provide the abstract in-line as text in the issue.
5. Follow your issue to respond to peer-review as it happens (feel free to update the submission!)
6. Browse <https://github.com/ResearchObject/ro2019/issues/> - feel free to contribute ad-hoc reviews to other submissions!

_Upon acceptance we will upload any inline abstracts to Zenodo to assign DOIs, assuming CC-BY-4.0 as license._

## Update Zenodo

In Zenodo you can augment most of the metadata by clicking "**Edit**" on your record. For instance, many authors prefer to update the "**Digital Object Identifier**" to the DOI from the the official proceedings.

Note that the uploaded files cannot be changed. However you may update your uploads in the Zenodo record by clicking **New Version**. Note that reviewers are not required to assess revisions added after the deadline, but this may be used for:
	
  * Providing updated article, links or resources requested by reviewers
  * On acceptance of an article, uploading the IEEE camera-ready author-version PDF with official DOI from IEEE
  * On eventual rejection, a revised white-paper or preprint submitted elsewhere
