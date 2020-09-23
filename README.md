# glutton
file _ingestion_ for legacy data content search.

lots of companies have a shared drive out there, _somewhere_ that houses a lot of documentation about applications, departments, people, so on so forth.

I suppose you could point something like (rip)grep at the top level directory and let it go to town, but (to my knowledge) they don't cache so you'd be re-grepping everytime you needed to find something new.

The idea for glutton is as follows - 3 parts to the application:

1. File ingestion.
2. Data Token storage (NOSQL or comparable tech for fuzzy string searches)
3. Web UI for performing the actual searching.
 

 # File Ingestion
 
 I'd like to write it in Rust :)
 
 # Data Storage / Lookup
 
 I saw a project called [Sonic](https://github.com/valeriansaliou/sonic) not too long ago, I'd like to see if it would work for what I'm imagining.
 
 # Web UI
 
 LMAO we'll get there when we get there. ([svelte](https://svelte.dev/) question mark?)
