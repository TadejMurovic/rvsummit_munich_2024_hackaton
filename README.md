Run in terminal:

git clone https://github.com/TadejMurovic/rvsummit_munich_2024_hackaton.git

and then run (copy all lines at once):

apt-get install zip unzip &&
cd rvsummit_munich_2024_hackaton &&
unzip hackaton_sw.zip &&
mv codasip_urisc_v/ ../codasip_urisc_v &&
mv hackaton_sw/ ../hackaton_sw  &&
cd .. &&
rm -rf rvsummit_munich_2024_hackaton/ &&
rm -rf codasip_urisc_v/work/*
