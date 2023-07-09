# RBC crawler

Main url: https://www.rbc.ru/

Pyhon notebook (rbc_crawler.ipynb) consist of class RBCparser, which has several methods:

1) __init__ - define main requset and soup
2) find_links - return the list of links for root link
3) find_all_links  - return the list of links for root link and for all links in find_links method
4) find_text - return dictioanary with all texts for each link in input parameters
5) find_title - return dictioanary with all titles for each link in input parameters
6) find_images - return dictioanary with all images for each link in input parameters
7) save_dict - save input dict/list in json format
