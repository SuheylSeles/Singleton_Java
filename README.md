# Singleton_Java
Java Singleton Pattern İlkeleri
Singleton pattern bir sınıftan birden fazla instance oluşmasını engeller ve sanal makinada oluşturulan tek instance’ın kullanılmasını garanti eder.
Singleton sınıfı, sınıfa ait instance’a ulaşmak için global erişim sağlamalıdır.
Singleton sınıfının constructor’ı private olmalıdır. Böylece o sınınftan yeni instance oluşturmak engellenmiş olur.
Singleton sınıfın instance’ı içeride private static olarak tutulmalıdır.
Tutulan instance’ı döndüren bir public static metoda sahip olmalıdır.
