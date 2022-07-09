# RPQ_QUERY

Q1: 

SELECT ?x ?y WHERE { ?x <http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf> ?y .}

Q2: 

SELECT ?x ?y WHERE { ?x <http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>* ?y .}

Q3:

SELECT ?x ?y WHERE { ?x <http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>* ?y .}

Q4:

SELECT ?x ?y WHERE { ?x (<http://swat.cse.lehigh.edu/onto/univ-bench.owl#headOf>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#memberOf>)*  ?y .}

Q5:

SELECT ?x ?y WHERE { ?x (<http://swat.cse.lehigh.edu/onto/univ-bench.owl#headOf>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#name>)* ?y .}

Q6: 

SELECT ?x ?y WHERE { ?x (<http://swat.cse.lehigh.edu/onto/univ-bench.owl#worksFor>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#knows>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>)* ?y .}

Q7:

SELECT ?x ?y WHERE { ?x <http://swat.cse.lehigh.edu/onto/univ-bench.owl#worksFor>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>* ?y .}

Q8:

SELECT ?x ?y WHERE { ?x (<http://swat.cse.lehigh.edu/onto/univ-bench.owl#worksFor>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>*)* ?y .}

Q9:

SELECT ?x ?y WHERE { ?x (<http://swat.cse.lehigh.edu/onto/univ-bench.owl#headOf>/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#subOrganizationOf>*/<http://swat.cse.lehigh.edu/onto/univ-bench.owl#name>)* ?y .}