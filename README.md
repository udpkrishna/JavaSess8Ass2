# JavaSess8Ass2

package Session8;

import java.util.HashSet;
import java.util.Iterator;
import java.util.Set;

public class Sess8Ass2 {
	public static void main(String[] args) {
	
		Set<Integer> set=new HashSet<Integer>();
		set.add(6);
		set.add(7);
		set.add(3);
		set.add(9);
		set.add(2);
		set.add(1);
		set.add(99);
		
		Iterator<Integer> itr=set.iterator();
		while(itr.hasNext()){
			Integer obj=itr.next();
			System.out.println(obj);
		}
		
	}

}
