# ddG
a simple repo for ddG calculations

first, place your input PDb into the input directory and change the name in the ddG_app.job file.
Next, navigate into 'mutfiles' and edit the input.txt file. Insert your mutations as the example indicates. then run the create_mutfiles script and generate the mutfiles for every mutation. CAVE: The script generates mutfiles for 3 chains. Change that if needed.

now just edit the start.sh script with the names of your mutation and sbatch thi script on the cluster.
