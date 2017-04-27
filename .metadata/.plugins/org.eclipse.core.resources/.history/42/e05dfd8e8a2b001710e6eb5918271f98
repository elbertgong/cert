package addCE;

import javax.persistence.Entity;
import javax.persistence.GeneratedValue;
import javax.persistence.Id;
import javax.persistence.Table;
 
@Entity
@Table
public class Attendee {
     
    @Id
    @GeneratedValue
    private Integer id;

    private String firstName;
    private String lastName;
    private String profession;
    private String licenseNum;
    private String country;
    private String accredDate;
    private String creditType;
    private String numCredits;
    private String emailAddr;
     
    public Attendee() {};
     
    public Attendee(Integer id, String firstName, String lastName, String profession,
    		String licenseNum, String country, String accredDate, String creditType,
    		String numCredits, String emailAddr) {
        this.id = id;
        this.firstName = firstName;
        this.lastName = lastName;
        this.profession = profession;
        this.licenseNum = licenseNum;
        this.country = country;
        this.accredDate = accredDate;
        this.creditType = creditType;
        this.numCredits = numCredits;
        this.emailAddr = emailAddr;
    }
    
    public void setId(Integer input) { this.id = input;}
    public void setFirstName(String input) { this.firstName = input;}
    public void setLastName(String input) { this.lastName = input;}
    public void setProfession(String input) { this.profession = input;}
    public void setLicenseNum(String input) { this.licenseNum = input;}
    public void setCountry(String input) { this.country = input;}
    public void setAccredDate(String input) { this.accredDate = input;}
    public void setCreditType(String input) { this.creditType = input;}
    public void setNumCredits(String input) { this.numCredits = input;}
    public void setEmailAddr(String input) { this.emailAddr = input;}
 
}