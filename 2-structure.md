I.  Structure
					•  See how HTML describes the structure of a web page
					•  Learn how tags or elements are added to your document
					•  Write your first web page
	A.  How pages use structure
		1.  Headlines, headings, forms: there are different structures out there.
	B.  Structuring Word documents
		1.  "Headings and subheadings often reflect a hierarchy of information"
		2.  e.g. HEADING -> Introduction or most important information -> Subheading -> Article
	C.  HTML Describes the Structure of Pages
		1.  We use structure the same way when we write pages.
		2.  Elements: Characters that live inside angled brackets
			a.  Usually 2 tags, opening and closing.
			b.  Tell the browser somethign about the information that sites between their opening and closing tags.
	D.  HTML Uses Elements to Describe the Structure of Pages: Illustration
		1.  Tags act like containers: they tell you something about the information that lies between their opening and closing tags.
		2.  <html> : indicates anything between it and closing </html> is html code.
		3.  <body> indicates taht anything between it and the closing tag should be shown in main browser window.
		4.  Words between h1 and /h1 are a main heading
		5.  Paragraph between p tags
		6.  h2 subheading
		7.  Another paragraph
		8.   Closing body tags
		9.  Closing html tags indicate end of html code.

	E.  Closer look at tags.
		1.  < >left and right angle brackets
		2.  / Forward slash

		Tags:
		<b> visual emphasis, no additional meaning.
		<i> italic, different from surrounding content, like technical terms, ships, foreign words, thoughts or other normally italicized terms.
		<sup> superscript
		<sub> subscript
		<br /> Line break inside the middle of a paragraph
		<hr /> Break between themes such as a change of topic in a book or a new scene in a play.
		Concept: White Space Collapse:
			Two or more spaces next to each other display as one space.  Line breaks are treated like single spaces.  Use to indent code for legibility.
		
		Semantic markup: Not intended to affect the structure of web pages but do add extra information to the pages.
		<em> allows you to indicate where an emphasis should be placed on selected words.
		<blockquote> Indicates a block of quotation.  Browsers often display the contents of these elements in a different way e.g. <em> usually italicized, <blockquote> usually indented.
		Purpose of semantic markup: Not to change the way a page looks but to accurately describe the content of a webpage because screen readers and search engines can use this extra information.
		<strong> Indicates that content has strong importance, defaults to bold.
		<em> Indicates emphasis that subtly changes the meaning of sentence.  Default: italicized.
		<blockquote cite="url"> Used for longer quotes by default.  Other tags still used inside.  Defaults to indented.
		<q cite="url"> Used for shorter quotes that sit within paragraphs.  Browsers supposed to put quotes around q elements but not all do.  May use the cite= attribute to indicate source.  Should be a URL with more information.
		<abbr title="Longname"> Used for abbreviations and acronyms.
		<cite> Used to indicate a piece of work like a book, film or research paper.  Should not be used for a person's name but is used as such.  By default rendered in italics.
		<dfn> Definition: Used to indicate the defining instance of a new term.  Some browsers default to italics, Safari and Chrome do not.
		<address> Contains contact details for the author of a page.  Often defaults to italics.  May include hCards in microformat.
		<ins>, <del>  Used to show content that has been inserted or deleted
		<s> Indicates something that is not longer accurate or relevant but should not be deleted.  Visually displayed with a strike through.