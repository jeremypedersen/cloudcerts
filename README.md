# What is this repository for? 

It holds "cram" notes to help prepare for various cloud certifications. All my notes are based on the cloud certification courses at [acloud.guru](https://acloud.guru). I recommend you take a full course (like the ones at acloud.guru) before sitting any certification exams: my notes are very brief and are intended mostly to help you review.

# How can I use these notes?

Feel free to use them for personal study. You can clone and edit as you wish. There is no explicit license on my notes.

My notes on each cloud provider's certifications are stored in appropriately named folders:
- abc: Alibaba Cloud
- aws: Amazon AWS
- azure: Microsoft Azure
- gcp: Google Cloud Platform

Right now I only have notes on AWS. I will generate additional note sets as I earn new certifications. 

# Can I download these notes to study offline? 

Yes! Here are links to PDF versions of my notes, which I created using Node's "markdown-pdf" tool:

- Alibaba Cloud
    - Coming soon!
- Amazon AWS:
    - AWS Developer Associate in [PDF format](https://s3.amazonaws.com/cloudcertnotes/aws_certified_developer_associate.pdf) and [HTML format](https://s3.amazonaws.com/cloudcertnotes/aws_certified_developer_associate.html)
- Microsoft Azure:
    - Coming soon!
- Google Cloud Platform
    - Coming soon!

# Build steps

Interested in turning your own markdown files into PDFs? The wonderful tool [Pandoc](https://pandoc.org/) can help! Check it out. I used it to generate the PDF and HTML versions of my notes, like so:

## Building PDFs (with link color highlighting)

`pandoc mydoc.md -t latex -o mydoc.pdf --variable urlcolor=cyan`

## Building HTML documents

`pandoc mydoc.md -t html -o mydoc.html`
