# Data

Publicly available CourseKata datasets for demonstrations. 

Resources (codebooks, documentation, scripts, etc.) can be found at [research.coursekata.org](research.coursekata.org). 

If you'd like to publish or present research using this data, please review and sign our [CourseKata Data Use Agreement for Researchers](https://docs.google.com/forms/d/e/1FAIpQLSecVJKONItq5fni8CLfXxvjTlNBcMoQityqkt_6sCJMjvwltQ/viewform).


## About the Raw Data Files

Go to [research.coursekata.org](research.coursekata.org) for more information about our datafiles. There, you can also find other relevant resources such as codebooks, processing files, survey overviews etc. 

In this publicly available repo, we have relatively raw files that we typically provide to CourseKata researchers:
- classes.Rdata
- responses.Rdata
- media_views.Rdata
- page_views.Rdata

However, we have also have two additional files similar to the files provided to the [ASA DataFest in 2024](https://ww2.amstat.org/education/datafest/index.cfm):
- checkpoints_eoc.Rdata
- checkpoints_pulse.Rdata


## Anonymized Further

All CourseKata data are anonymized but this public version is anonymized even further in that:

- open responses or short text have been removed from responses.Rdata (replaced with NA) 
- removed coding responses have been removed from responses.Rdata (replaced with NA) 

If you would like these written responses to analyze for research purposes, please [contact us](research@coursekata.org) and become part of our CourseKata Research network.


## How to Cite CourseKata Data in Research Reports

If you found this data helpful, we would love to hear from you. CourseKata is a non-profit project funded primarily by philanthropy. We provide all of our data free to researchers, but expect to be credited as the source of the data in any resulting research reports and conference presentations. This could be done in the methods or introduction section of a report, or wherever the data are described. 

In addition, researchers using CourseKata data agree to send copies of all reports, conference presentations, and publications to CourseKata at [info@coursekata.org](info@coursekata.org).

### Example Citations (feel free to copy and paste!)

> Participants used an online interactive statistics and data science textbook developed by CourseKata (https://coursekata.org; Son & Stigler, 2017-2022). [update 2022 to current year]

> The version of the textbook used in this study has twelve chapters and covers material typically covered in an introductory statistics course (https://coursekata.org; Son & Stigler, 2017-2024).

> The book emphasizes the concept of statistical modeling as a means of making the content more coherent for students and instructors (Son et al., 2021), and is based on a pedagogical approach referred to as practicing connections (Fries et al., 2021).

> The CourseKata materials were developed as part of a larger project (the Better Book project) that is exploring new ways of using research to improve teaching, learning, and curriculum development (Stigler et al. 2020).

> All data presented here were collected and shared with the authors by CourseKata (https://coursekata.org).

### References (in APA format)

- Fries, L., Son, J. Y., Givvin, K. B., & Stigler, J. W. (2021). Practicing connections: A framework to guide instructional design for developing understanding in complex domains. *Educational Psychology Review, 33*(2), 739-762.
- Son, J.Y. & Stigler, J.W. (2017-2024). Statistics and data science: A modeling approach. Los Angeles: CourseKata, https://coursekata.org/preview/default/program. Currently available in 7 versions.
- Son, J. Y., Blake, A. B., Fries, L., & Stigler, J. W. (2021). Modeling first: Applying learning science to the teaching of introductory statistics. *Journal of Statistics and Data Science Education, 29*(1), 4-21.
- Stigler, J. W., Son, J. Y., Givvin, K. B., Blake, A. B., Fries, L., Shaw, S. T., &  Tucker, M. C. (2020). The Better Book approach for education research and development. *Teachers College Record, 122*(9), 1-32.