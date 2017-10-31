# Social Network Analysis
# Amazon Book Recommendation System


### Data source
Stanford Network Analysis Project http://snap.stanford.edu \
Amazon product co-purchasing network metadata http://snap.stanford.edu/data/amazon-meta.html

### Dataset information
The data was collected by crawling Amazon website and contains product metadata and review information about 548,552 different products (Books, music CDs, DVDs and VHS videotapes)

### Dataset statistics
- Products:  548,552
- Product-Project Edges:  1,788,725
- Reviews:  7,781,990
- Product category memberships:  2,509,699
- Products by product group
- Books:  393561
- DVDs:  19828
- Music CDs:  103144
- Videos:  26132

### Data format
* Id: Product id (number 0, ..., 548551)
* ASIN: Amazon Standard Identification Number
* Title: Name/title of the product
* Group: Product group (Book, DVD, Video or Music)
* SalesRank: Amazon Sales rank
* Similar: ASINs of co-purchased products (People who buy X also buy Y)
* Categories: Location in product category hierarchy to which the product belongs
* Reviews: time, user id, rating, total number of votes on the review, total number of helpfulness votes

### Source (citation)
J. Leskovec, L. Adamic and B. Adamic. [The Dynamics of Viral Marketing](http://www.cs.cmu.edu/~jure/pubs/viral-tweb.pdf). ACM Transactions on the Web (ACM TWEB), 2007.
