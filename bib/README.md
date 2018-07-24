# The Bib Submodule

### How to use

##### Add to your project
	
	git submodule add git@github.com:hemingcui/bib.git ./bib


##### Start from an existing project.

	cd bib
	git submodule init
	git submodule update
	git checkout master 
	
##### Update

	git submodule foreach git pull
	//OR
	cd bib
	git pull
	
	


### Rules for updating:

1. **Don't** change or delete existing entries. It will cause errors on others' references.
  

2. Before adding a new entry, **search** by its paper name and authors to make sure it is not already included.  

3. Follow the naming format of `system name:conference` (e.g., `crane:sosp15`), `author:conference/keyword` (e.g., `lamport98parttime`) or some special keywords easy to understand and remember (e.g., `paxos:fast`).  
   **Don't use a very long key with some random numbers**

4. **Group** the papers in the same conference together. You can add entries to the end while writing papers, but please put them into suitable position for others future usage.

