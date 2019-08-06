import java.security.MessageDigest;
import java.security.NoSuchAlgorithmException;

public class SHA512 {
  public static String encrypt(String paramString1, String paramString2) {
    try {
      null = MessageDigest.getInstance(paramString1);
      null.update(paramString2.getBytes());
      byte[] arrayOfByte = null.digest();
      StringBuffer stringBuffer = new StringBuffer();
      for (byte b = 0; b < arrayOfByte.length; b++)
        stringBuffer.append(Integer.toString((arrayOfByte[b] & 0xFF) + 256, 16).substring(1)); 
      return stringBuffer.toString();
    } catch (NoSuchAlgorithmException paramString1) {
      paramString1.printStackTrace();
      return null;
    }  
  }
}
