docker run --name test-nginx  -v C:\Users\User\IdeaProjects\Examples\TestNginx\nginx_learning\test-default.conf:/etc/nginx/nginx.conf:ro -p 9004:9004 -d  nginx nginx-debug -g 'daemon off;'


https://localhost:8080/api/v1/services/121463/status?user_id=1494&user_token=d98ca242e36a447e99f63d1116442fed

tail -f /var/log/nginx.access_log 