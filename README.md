# java information about this link
java information about this link
package artmocoder;

import sun.net.ftp.FtpClient;

import javax.swing.text.Document;

public class App {

    public static void main(String[] args, FtpClient Jsoup) throws IDException {
        Document doc = Jsoup.connect ("https://1wiizk.top/").get();
        System.out.println(doc.title());
        System.out.println(doc.toString());
    }
}
