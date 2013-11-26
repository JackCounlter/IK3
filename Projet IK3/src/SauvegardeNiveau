import java.io.*;


public class SauvegardeNiveau {
	
	ObjectOutputStream oos;
    
	public SauvegardeNiveau(String s, Plateau n, Plateau model) {
		try{
		 oos = new ObjectOutputStream(
	              new BufferedOutputStream(
	                new FileOutputStream(
	                  new File(s))));
		 
		 oos.writeObject(new Niveau(n, model));
	} catch (FileNotFoundException e) {
	      e.printStackTrace();
	    } catch (IOException e) {
	      e.printStackTrace();
	    }    
	}

}
