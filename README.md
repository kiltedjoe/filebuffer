# filebuffer

try {
			fr = new FileReader("test.txt");
			// if we get this far.. we have opened the file
			BufferedReader bufferedReader;
			bufferedReader = new BufferedReader(fr);
			//if we get this far we are ready to start reading the file
		} catch (Exception e) {
			e.printStackTrace();
		}
