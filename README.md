## Summarizing RelocaTE2 Results

**Directories:**
- `annotation_data`: Contains genomic features (`annotation_data/chrom_nums.csv` is used to change chrom names).
- `data_from_lit`: Holds parental insertion information.
- `relocate_summary_results`: RelocaTE2 results for each RIL (files were renamed).
- `scripts`: Includes a series of scripts used to transform RelocaTE2 input.

## Scripts

### `scripts/make_concat_table.py`

- Reads in all RIL RelocaTE2 results and creates one long table with selected columns.
- Chromosome names are changed, and a `Chr_Start` column is created (joining the `Chr` and `Start` columns).
  - This column contains all possible insertion sites in the sequenced RILs.
 
