# SomeNew
new project let's go!
/**
	 * 获取当前时间的年、月
	 */
	public static String getYD(){
		String a="";
		SimpleDateFormat fomt=new SimpleDateFormat("yyyy-MM:");
		a=fomt.format(new Date());
		return replaceYM(a);
	} 
