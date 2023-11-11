# Mongo
### Download “Books 5-core (8,898,041 reviews)” From the link “http://jmcauley.ucsd.edu/data/amazon/” and insert directly to MongoDB using mongo import command

If you receive an error similar to the following when starting mongod  
Failed to start mongod.service: Unit mongod.service not found.  
Run the following command first:  
sudo systemctl daemon-reload  

* check if service is running:  
sudo systemctl status mongod  

* Stop MongoDB:  
sudo systemctl stop mongod  

* Restart MongoDB:  
sudo systemctl restart mongod  

* Begin using MongoDB:  
mongosh  
