# Word_count_using_an_docker
word count algorithmn in python running trough the windows powershell 
first install docker 
after in your powershell, run this function to connect to your docker environnment and run a first python file 
docker run -p 4040:4040 -v C:\Users\Theom\Downloads\BBAdocker2:/opt/spark/work-dir -t apache/spark-py /opt/spark/bin/spark-submit --master="local[*]" ./pi.py

do that with the python file that you want 
