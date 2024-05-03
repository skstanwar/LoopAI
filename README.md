
# APIs :

1) Trigger Report
   curl --request GET \
  --url http://localhost:8000/store/9200325206334396031/trigger_report/ \
  --header 'Content-Type: application/json' \
  --data '	'
   
3) Get Report
   curl --request POST \
  --url http://localhost:8000/store/get_report/ \
  --header 'Content-Type: application/json' \
  --data '{
	"report_id": 74
	
}'
