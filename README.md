fio version: 3.22
OS: CENTOS 6.9
./fio --filename=read.txt --ioengine=sync --direct=0 --rw=read --bs=4k --numjobs=1 --iodepth=4 --name=read_perf  --filesize=1G
./fio --filename=write.txt --ioengine=sync --direct=0 --rw=write --bs=4k --numjobs=1 --iodepth=4 --name=write_perf  --filesize=1G

