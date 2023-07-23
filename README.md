package comput;
public   class Desktopp implements Software,Hardware {
	public void empId() {
		System.out.println("Destop models Dell,Lenova,Hp");
	}
	@Override
	public void softwareResources() {
		System.out.println("MACOS,WINDOWS,LINUX");
	}
	@Override
	public void hardwareResources() {
		System.out.println("RAM,CFIF");		
	}
	public static void main(String[] args) {
		Desktopp d=new Desktopp();
		d.empId();
		Software s=new Desktopp();
		s.softwareResources();
		Hardware h=new Desktopp();
		h.hardwareResources();
	}
}
