This file provides an outline of documentation specifically for journal editors.

# Preliminary Remarks

Law & Space is built using Jekyll, a static website generator, and hosted publicly on Github. Static websites are more stable, load faster, typically cost little to nothing, have a large open-source, developer community, and facilitate greater intellectual transparency, particularly when combined with Github. The main downside is that academics who are most likely to contribute to, and serve as editors for, Law & Space may not have the technological skill set to contribute directly to the development of the journal, since static site generators do not typically have a user-friendly interface. This guide attempts to provide an outline for contributors and editors who wish to level-up these skills and contribute directly, though this is absolutely not a requirement.

# Required skills

There are several skills required for working with the Law & Space website.

- writing in plain text and Markdown
- understanding basic Github processes
- compiling websites using Jekyll

# Understanding Git and Github

Git is a version control system that allows several people to work on a project simultaneously, then recombine the work to produce a finished version. Git emerged out of the tech industry where teams of programmers needed a way to work on large projects (say, a single program or an entire operating system). However, Git works well for any type of project that is mostly based on text files and where success is conditioned on the contribution of a team.

To put it simply, Git allows you to create your own version of a project, edit that project, create snapshots of your progress over time, then add your changes back into some finalized version. And because Git keeps track of the project's history, you can roll back to previous versions at any time to recover lost information. Git can be run on a single computer, but Github essentially takes these functionalities of Git and puts them online with some added features for teams.

# Understanding Markdown

Because plain text files (rather than rich text or proprietary file formats like Apple Pages or MS Word) are central to all computer programming and therefore to Github, programmers needed a way to add visual structure to these files to improve readibility when writing documents rather than programs. Moreover, plain text files are useful for researchers, since plain text files can be opened by virtually any text editor and are indifferent to file formats. If you have an old MS Word file or old Pages file, you may not be able to open it with current software, and to share proprietary files, your collaborator needs to have the same software you have. Plain text files don't have these limitations. But it is still very helpful to be able to add headings, emphasis, etc., to plain text files.

Markdown fills this gap by providing a standard way of doing this. For instance, headings are marked off with a hash-sign (\# see the headings in this document), emphasis is represented using asterisks (\*) around words **like this**, and hyperlinks are added using brackets and parentheses like this: \[the text you want to be visible\]\(the actual URL that you want people to go to when the click on the text\). Notice that if you want those characters to be treated as just the characters rather than treated like syntax, you can add a backslash before it.

Once a document is written in Markdown, it can be processed based on the needs of whichever website is using that file. Today, most writing tools on the internet--including Wordpress, Github, and even some word processors now--recognize and use Markdown syntax, which means that if you write something in Markdown *first*, you will likely be able to publish that same text in multiple places without having to reformat it. Markdown files are represented using the file extension ".md", but otherwise are no different than a plain text file that ends with the extention ".txt".

Note that while there are various "flavors" of Markdown, some of which add functionality and can get really full-featured, the most common type of Markdown is called "Github flavored markdown". For reasons that are hopefully obvious at this point, Github's ubiquity contribute to it being the standard-bearer for what counts as "normal" Markdown.

# Understanding Jekyll

Jekyll recognizes Markdown syntax and uses it to build web pages for Law & Space. Therefore, all visible content on the Law & Space website is written in plain text files using Markdown. There are also other essential files that should not be edited by anyone without the proper knowledge and skills.

Jekyll is a program that takes a set of files and uses those files to build a static website. The website is static because rather than using a live database or other plugins to push and pull information to the website based on the user, static websites simply sit there, unchanging, until an editor actively edits a file or until someone recompiles the website using Jekyll to upate it.

Jekyll runs on a computer, not in the cloud. (There are ways around this, but we are not using those methods right now.) Currently, the only person who is set up to do a website rebuild is Austin.

Text files that represent individual pages (i.e. our Purpose page) or individual blog posts (just the body of the post, not the heading information) can be edited without rebuilding the website.

However, Jekyll uses other information contained in the text files to build parts of the website. For instance, each blog post has a "heading" area that includes metadata about the post, such as the author name, the title, the date, etc. That information must be formatted in a very specific way (e.g. using YAML syntax) and the consequences of changing that information affect not just one file but other files on the website. Therefore, you are strongly discouraged from editing that information without additional conversation.

# Website Conventions

The following conventions should be used when creating a new post.
- The text file for a post should start with the date of the post formatted as follows: "YYYY-MM-DD-title-title-title.md"
- all files associated with that post should be stored in a folder specifically for that post and the titles formatted using the same date format up front followed by a minimal description or figure number. (It may be advantageous to change this to a purely descriptive file name if we decide we want to use images more than once? Undecided.)
