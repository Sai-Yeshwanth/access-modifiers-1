class Jala {
	private String name="Sai";
	private void getname()
	{
		System.out.println(name);
	}
	public static void main(String[] args) {
		Jala j = new Jala();
		j.getname();
	}
}
class Add extends Jala{
	Add a = new Add();
	a.getname();    // Error occurs here
}
