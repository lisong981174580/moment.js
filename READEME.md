      ### 很好用的时间格式化工具
    ```
        //当前时间
         console.log(moment());

        //时间戳 
        console.log(moment().valueOf());

        //格式化时间
         console.log(moment().format('YYYY'));   
         console.log(moment().format('YYYYMM'));   
         console.log(moment().format('YYYYMMDD'));   
         console.log(moment().format('YYYY-MM-DD hh:mm:ss'));   
         console.log(moment().format('YYYY/MM/DD hh:mm:ss')); 

         //截取时间
    	console.log(moment().subtract(10, 'year').format('YYYY-MM-DD'))
    	console.log(moment().subtract(10, 'month').format('YYYY-MM-DD'))
    	console.log(moment().subtract(10, 'days').format('YYYY-MM-DD'))
    	console.log(moment().subtract(10, 'hour').format('YYYY-MM-DD  hh:mm:ss'))

    	console.log(moment().add(10, 'year').format('YYYY-MM-DD'))
    	console.log(moment().add(10, 'month').format('YYYY-MM-DD'))
    	console.log(moment().add(10, 'days').format('YYYY-MM-DD'))
    	console.log(moment().add(10, 'hour').format('YYYY-MM-DD  hh:mm:ss'))


    	//取时间的起点
    	 console.log( moment().startOf('day').format('YYYY-MM-DD hh:mm:ss'))
    	 console.log( moment().startOf('month').format('YYYY-MM-DD hh:mm:ss'))
    	 console.log( moment().startOf('year').format('YYYY-MM-DD hh:mm:ss'))

    	 //时间的终点
    	 console.log( moment().endOf('day').format('YYYY-MM-DD hh:mm:ss'))
    	 console.log( moment().endOf('month').format('YYYY-MM-DD hh:mm:ss'))
    	 console.log( moment().endOf('year').format('YYYY-MM-DD hh:mm:ss'))

         //距离现在多远
        console.log( moment("20111031").fromNow());
	    console.log( moment("20120620").fromNow()); 

        //文字化时间
	    console.log(moment().calendar());  

	    //格式化时间另外的方式
	    console.log(moment().format('l'));    
		console.log(moment().format('LL'));   
		console.log(moment().format('ll'));   
		console.log(moment().format('LLL'));  
		console.log(moment().format('lll'));  
		console.log(moment().format('LLLL')); 
		console.log(moment().format('llll')); 

		//格式化时间
		console.log(moment('20111110').format("YYYY-MM-DD"))
		console.log(moment(1529465603870).format("YYYY-MM-DD"))
		console.log(moment('2011-11-10').format("YYYY-MM-DD"))
```
