Go Daddy : 

	Used to buy domain , create DNS records , nameservers 
	An alternative for Route53 in aws 

Task : 

	https://pensico.com  -> hello world
	https://www.pensico.com -> Hello world

	guna.pensico.com -> Hello from guna 
	rishika.pensico.com -> hello from rishika 


	www.pensico.com/hello -> hi 
	www.pensico.com/*   -> 404 page 

	*.pensico.com -> cheese 


Deploy this html files[static web hosting] using s3 , route53 , Cloudfront(CDN) , ACM[Amazon Certificate Manager] 

Two approaches : 

	1. Create a single bucket which contains all the files like index.html[helloworld] , guna/index.html[Hello from guna] , rishika/index.html[Hello from rishika] , cheese.html[Cheese] and configure them in route53 which is not possible 

	2. Create different s3 buckets , 
