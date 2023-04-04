# 3package ch06;

class Tv{
	// Tv의 속성(멤버변수)
	String color;        //색상
	boolean power;       //전원상태(on/off)
	int channel;         //채널
	
	
	// Tv의 기능(매서드)
	void power()  { power  =  !power;}  //tv를 켜거나 끄는 기능을 하는 ㅁ
	void channelUp(){ ++channel;}       //tv의 채널을 높이는 기능을 하는 메서드
	void channelDown() { --channel;}
	
	
	
	
	
}

public class ex6_1 {

	public static void main(String[] args) {
		// TODO Auto-generated method stub

		
		Tv t;
		t = new Tv();
		
		t.channel =7;
		t.channelDown();
		System.out.println("a현재  채널은"+ t.channel+"입니다.");
		
		
		t.channelUp();
		System.out.println("b현재 채널은"+t.channel+"입니다");
		
		
		
		
		
		
	}

}
