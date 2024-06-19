Run in terminal (copy all lines at once):

git clone https://github.com/TadejMurovic/rvsummit_munich_2024_hackaton.git &&
apt-get install zip unzip &&
cd rvsummit_munich_2024_hackaton &&
unzip hackaton_sw.zip &&
mv codasip_urisc_v/ ../codasip_urisc_v &&
mv hackaton_sw/ ../hackaton_sw  &&
cd .. &&
rm -rf rvsummit_munich_2024_hackaton/ &&
rm -rf codasip_urisc_v/work/* &&
sed -i '44,46d' codasip_urisc_v/options.conf &&
sed -i '21,34d' codasip_urisc_v/options.conf
sed -i '1d' codasip_urisc_v/ip.conf && 
sed -i '1iconfiguration = "32I"' codasip_urisc_v/ip.conf  
