sudo docker build -t databport-harbor.databport.it-scholar.com/seminar/ben-coeppicus:v4 .
sudo docker push databport-harbor.databport.it-scholar.com/seminar/ben-coeppicus:v4
cd mychart
helm upgrade ben-coeppicus .