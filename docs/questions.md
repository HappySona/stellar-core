
How do we submit tx to the network?
	- some process that runs and converts between json-rpc and our peer code
	- hayashi includes a webserver

How do we give commands to a running stellarx?
	

Do we keep full entries in the BucketList?


What is the file format for the history?


Are we charging enough for storage?


What do we do about tx that make it into the applied txset but have too low a max fee? 
	Do we consume the seq num?
	Do we charge the max fee and not apply them? 
	Do we just ignore them?
	Do we let them get by for free?
	

How does the network start up?
	validator starts with --new
	DB is cleared
	Hash genesis ledger
	Start FBA with empty txSet
	FBA will hang until a quorum is also started with --new