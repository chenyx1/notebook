# 数组转换的list一个常见问题

由数组转换的list,只能循环遍历，而增加元素，删除元素，这是为何？下图代码执行竟然出错！

public static void addList() {

   String [] arrs = {"1","2,","3"};

   List<String> stringList = Arrays.asList(arrs);

   stringList.add("4");

   System.out.println(stringList.size());

}



答：通过源码发现，Arrays.asList()返回的ArraryList是Arrays内部类。该类并没有提供增删该方法。当调用对应的方法是，其实是调用基类AbstractList的对应的方法，基类的方法会抛出，UnsupportedOperationException