package phone_book;

public class Date {
	private int day;
	private int month;
	private int year;

	public Date(){
		this.day = 0;
		this.month = 0;
		this.year = 0;
	}

	public Date(int day, int month, int year){
		this.day = day;
		this.month = month;
		this.year = year;
	
	
	if      ((month == 12 && day >= 22 && day <= 31) || (month ==  1 && day >= 1 && day <= 19))
        System.out.println("Capricorn");
    else if ((month ==  1 && day >= 20 && day <= 31) || (month ==  2 && day >= 1 && day <= 17))
        System.out.println("Aquarius");
    else if ((month ==  2 && day >= 18 && day <= 29) || (month ==  3 && day >= 1 && day <= 19))
        System.out.println("Pisces");
    else if ((month ==  3 && day >= 20 && day <= 31) || (month ==  4 && day >= 1 && day <= 19))
        System.out.println("Aries");
    else if ((month ==  4 && day >= 20 && day <= 30) || (month ==  5 && day >= 1 && day <= 20))
        System.out.println("Taurus");
    else if ((month ==  5 && day >= 21 && day <= 31) || (month ==  6 && day >= 1 && day <= 20))
        System.out.println("Gemini");
    else if ((month ==  6 && day >= 21 && day <= 30) || (month ==  7 && day >= 1 && day <= 22))
        System.out.println("Cancer");
    else if ((month ==  7 && day >= 23 && day <= 31) || (month ==  8 && day >= 1 && day <= 22))
        System.out.println("Leo");
    else if ((month ==  8 && day >= 23 && day <= 31) || (month ==  9 && day >= 1 && day <= 22))
        System.out.println("Virgo");
    else if ((month ==  9 && day >= 23 && day <= 30) || (month == 10 && day >= 1 && day <= 22))
        System.out.println("Libra");
    else if ((month == 10 && day >= 23 && day <= 31) || (month == 11 && day >= 1 && day <= 21))
        System.out.println("Scorpio");
    else if ((month == 11 && day >= 22 && day <= 30) || (month == 12 && day >= 1 && day <= 21))
        System.out.println("Sagittarius");
    else
        System.out.println("Illegal date");

}
	
		
	/**
	 * @return the day
	 */
	public int getDay() {
		return day;
	}

	/**
	 * @param day the day to set
	 */
	public void setDay(int day) {
		this.day = day;
	}

	/**
	 * @return the month
	 */
	public int getMonth() {
		return month;
	}

	/**
	 * @param month the month to set
	 */
	public void setMonth(int month) {
		this.month = month;
	}

	/**
	 * @return the year
	 */
	public int getYear() {
		return year;
	}

	/**
	 * @param year the year to set
	 */
	public void setYear(int year) {
		this.year = year;
	}
	
	



	public String toString(){
		return this.day + "/" + this.month + "/" + this.year;
	}


}


