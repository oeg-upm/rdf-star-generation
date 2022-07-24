# JSON results merged
Some quick answer to the results in this folder

- These are the results obtained after applying the mapping rml-map-merged.ttl to the merged_json.json file. The merged JSON file contains all the JSON files obtained in somef as a single unified JSON file. The command used to produce this file is `jq -s 'flatten' oeg_json/*.json > merged_json.json`
- The results (results.nt) contain the triples directly produced by morph. Warning: the number of lines of this file is around 300 triples lower than the one obtained with separated files because this one does not have repeated labels. The previous results were obtained by merging separated nt files, and therefore contain the same labels multiple times.
