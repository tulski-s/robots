# robots

***About
Main idea behind proxyHarvester is to get as reliable free proxy list as possible and maintaining it in real time. First thing harvester is doing is scraping all defined free proxy lists. Next, it check if each single proxy is healthy or sick. Sick proxies (most of them... free proxies are crap...) are removed from list. Healthy proxies are stored and constantly checked if still healthy. Healthy proxies are stored in python pickle file each 30s. To get as good proxy list as possible, harvester should run while whole scrapping processes.
