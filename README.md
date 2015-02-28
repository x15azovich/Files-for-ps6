# Files-for-ps6
public class File {
	
	public void Append(String array) {
		try (PrintWriter out = new PrintWriter(new BufferedWriter(
				new FileWriter("Merge.txt", true)))) {
			out.print(array);
			
		} catch (IOException e) {
			// exception handling left as an exercise for the reader
		}
	}
}





import java.io.BufferedWriter;
import java.io.FileWriter;
import java.io.IOException;
import java.io.PrintWriter;


public class File1 {
	public void Append(String array) {
		try (PrintWriter out = new PrintWriter(new BufferedWriter(
				new FileWriter("SmallArrays.txt", true)))) {
			out.print(array);
			
		} catch (IOException e) {
			// exception handling left as an exercise for the reader
		}
	}
}





import java.io.BufferedWriter;
import java.io.FileWriter;
import java.io.IOException;
import java.io.PrintWriter;


public class File2 {
	public void Append(String array) {
		try (PrintWriter out = new PrintWriter(new BufferedWriter(
				new FileWriter("ArrayInOrder", true)))) {
			out.print(array);
			
		} catch (IOException e) {
			// exception handling left as an exercise for the reader
		}
	}
}


import java.io.BufferedWriter;
import java.io.FileWriter;
import java.io.IOException;
import java.io.PrintWriter;


public class File3 {
	public void Append(String array) {
		try (PrintWriter out = new PrintWriter(new BufferedWriter(
				new FileWriter("Auxillary.txt", true)))) {
			out.print(array);
			
		} catch (IOException e) {
			// exception handling left as an exercise for the reader
		}
	}
}




import java.io.BufferedWriter;
import java.io.FileWriter;
import java.io.IOException;
import java.io.PrintWriter;


public class File4 {
	public void Append(String array) {
		try (PrintWriter out = new PrintWriter(new BufferedWriter(
				new FileWriter("Improvements.txt", true)))) {
			out.print(array);
			
		} catch (IOException e) {
			// exception handling left as an exercise for the reader
		}
	}
}


import java.io.BufferedWriter;
import java.io.FileWriter;
import java.io.IOException;
import java.io.PrintWriter;


public class File5 {
	public void Append(String array) {
		try (PrintWriter out = new PrintWriter(new BufferedWriter(
				new FileWriter("Median3.txt", true)))) {
			out.print(array);
			
		} catch (IOException e) {
			// exception handling left as an exercise for the reader
		}
	}
}













import java.io.BufferedWriter;
import java.io.FileWriter;
import java.io.IOException;
import java.io.PrintWriter;


public class File6 {
	public void Append(String array) {
		try (PrintWriter out = new PrintWriter(new BufferedWriter(
				new FileWriter("Quick.txt", true)))) {
			out.print(array);
			
		} catch (IOException e) {
			// exception handling left as an exercise for the reader
		}
	}
}


