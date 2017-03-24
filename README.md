Setup on new machine Ubuntu 14.04

1. RVM

	https://www.digitalocean.com/community/tutorials/how-to-install-ruby-on-rails-on-ubuntu-14-04-using-rvm

2. MYSQL

	https://www.digitalocean.com/community/tutorials/how-to-install-mysql-on-ubuntu-14-04

3. POSTGRESQL

	https://www.digitalocean.com/community/tutorials/how-to-install-and-use-postgresql-on-ubuntu-14-04

4. PgAdmin-3

	sudo apt-get update
	sudo apt-get install pgadmin3

5. MongoDB-3

	https://www.digitalocean.com/community/tutorials/how-to-install-mongodb-on-ubuntu-14-04

6. Mysql Workbench

	wget http://dev.mysql.com/get/mysql-apt-config_0.3.5-1ubuntu14.04_all.deb
	sudo dpkg -i mysql-apt-config_0.3.5-1ubuntu14.04_all.deb
	sudo apt-get install mysql-workbench 
	mysql-workbench –version

7. ElasticSearch install

	sudo add-apt-repository -y ppa:webupd8team/java
	sudo apt-get update
	sudo apt-get -y install oracle-java8-installer
	https://www.elastic.co/guide/en/elasticsearch/reference/5.2/deb.html

	check elasticsearch is install or not=>
	
 		curl -XGET 'localhost:9200/?pretty'
		
 	Success response=>
	
				 		 {
							  "name" : "d1RaFpY",
							  
							  "cluster_name" : "elasticsearch",
							  
							  "cluster_uuid" : "uWdpuQEQTyWlNMCH2iKWhQ",
							  
							  "version" : {
							  
							    "number" : "5.2.2",
							    
							    "build_hash" : "f9d9b74",
							    
							    "build_date" : "2017-02-24T17:26:45.835Z",
							    
							    "build_snapshot" : false,
							    
							    "lucene_version" : "6.4.1"
							    
							  },
							  
							  "tagline" : "You Know, for Search"
							  
							}
