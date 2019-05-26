# Execution

`docker run -e DISPLAY=`ifconfig | grep -A 4 'en1' | grep net | cut -d ' ' -f 2`:0 crrossss/xclock`
