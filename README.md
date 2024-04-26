


## Prepare db records

```bash
zcat SILVA_138.1_SSURef_tax_silva_full_align_trunc.fasta.gz | grep '>' > ref.headers
cut -f 1 -d ' ' ref.headers > ref.ids
grep genus tax_slv_ssu_138.1.txt > genera.txt
```
