# fb-extractor
facebook message extractor

Extract Facebook Messenger (com.facebook.orca & com.facebook.katana)

1. Extract threads_db2 and contacts_db2 from /com.facebook.orca/database & /com.facebook.katana/database
2. Put inside fbmsg-extractor folder
3. Open command window here from inside fbmsg-extractor folder
4. Type:

	python fbmsg-extractor.py -t threads_db2 -c contacts_db2 -x contacts.tsv -z messages.tsv

5. Results are contacts.tsv and messages.tsv

Modified from  cheeky4n6monkey/4n6-scripts/fbmsg-extractor.py

Credits: cheeky4n6monkey
