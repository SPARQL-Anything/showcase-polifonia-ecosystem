List component files
```
fx -q queries/list-components.sparql -o data/list-components.csv -f CSV
```
Generate KG data
```
fx -q queries/components-to-rdf.sparql -i data/list-components.csv -f TTL -o data/components/component
```

