# Easy_Daily
convenient command-lines

## Synteny with NGenomeSyn
 /home/gaoshan/software/NGenomeSyn/NGenomeSyn/bin/GetTwoGenomeSyn.pl -InGenomeA zen1.bed.fa -InGenomeB zen2.bed.fa -OutPrefix zen1tozen2 -MinLenA 5 -MinLenB 5 -MappingBin minimap2 -BinDir /home/gaoshan/Y/pkgs/minimap2-2.30-h577a1d6_0/bin/ -MinAlnLen 300
 /home/gaoshan/software/NGenomeSyn/NGenomeSyn/bin/NGenomeSyn -InConf zen1tozen2.conf1 -OutPut zen1tozen2.conf1
