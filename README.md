# data
run commands

docker run --rm -it nanozoo/guppy_gpu:4.4.1-1--a3fcea3

guppy_basecaller --print_workflows|cut -f 1 -d " " | grep "FLO" | sort | uniq  

-->flowcells

copy & paste  in an empty .txt file and upload here https://github.com/t3ddezz/data/blob/main/flowcell_data.txt


guppy_basecaller --print_workflows|cut -f 2 -d " " | grep "[V,S][Q,S]K" | sort | uniq  

-->sequencing kits

copy & paste each in an empty .txt file and upload here https://github.com/t3ddezz/data/blob/main/sequencing_data.txt


