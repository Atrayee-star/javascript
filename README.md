<html>
<head>
<title>name</title>
</head>
<body>
<script>


	var a,b,c,d,e;
	//Here all the cases (13/2) is replaced by x 
	// And x will always give integer value
	var x=parseInt(13/2);
	
	
	for(a=1;a<=13;a++)
	{
		for(b=1;b<(40-a);b++)
		{
			document.write("&nbsp; ");
		}
		if(a==((x)+1))
		{
			for(d=1;d<(2*a);d++)
			{
				if((d%2)!=0)
				document.write("*");
				else
				document.write("&nbsp; ");
			}
		}
		else
		{
			for(c=1;c<(2*a);c++)
			{
				if(c==1||c==((2*a)-1))
				{
					document.write("*");
				}//;
				else
				{
					document.write("&nbsp; ");//printf(" ",c);
				}
			}
		}
		// for the s
		for(b=1;b<(40-a);b++)
		{
			document.write(" ");
		}
		if(a==1||a==((x)+1)||a==13)
		{
			if(a==1)
			{
			for(d=1;d<=(((x)+1));d++)
			{
				if(d%2==0)
				document.write("*");
				else
				document.write("&nbsp; ");
			}
			}
			else if(a==((x)+1))
			{
				for(d=1;d<=(((x)-1));d++)
			{
				if(d%2==0)
				document.write("*");
				else
				document.write("&nbsp; ");
			}
			}
			else
			{
				for(d=1;d<=(((x)-1));d++)
			{
				if(d%2!=0)
				document.write("*");
				else
				document.write("&nbsp; ");
			}
			}
		}
		else
		{
			if(a<((x)+1))
			{
			for(e=1;e<=x;e++)
				{
				if(e==(1))
				{
					document.write("*");
				}
				else
				{
					document.write("&nbsp; ");
				}
				}
			}
			else
			{
				for(e=1;e<=(x);e++)
				{
				if(e==(x))
				{
					document.write("*");
				}
				else
				{
					document.write("&nbsp; ");
				}
				}
			}
		}
		document.write("<br/>");
	}
	

</script>
</body>

</html>
