# Temiz Kod Rehberi

## İsimlendirmeler
- İsimlendirme, isimlendirilen şeyin neden var olduğunu, ne yaptığını ve nasıl kullanıldığını açıklar nitelikte olmalıdır.

- Birbirine benzeyen uzun değişken isimlendirmelerinden kaçınılmalıdır çünkü otomatik kod tamamlama özelliğine sahip editör veya geliştirme ortamlarında hatalara yol açabilir.

- İsimlendirmeler birbirinden ayırt edilebilir olmalı, kafa karışıklığına yol açmamalıdır.\
Örneğin; "Product", "ProductData", "ProductInfo" gibi birbirine benzeyen ancak farklı amaçlara hizmet eden tanımlamalardan kaçınılmalıdır.

- Telaffuz edilebilir isimlendirmeler kullanılmalıdır.\
Örneğin "private Date genymdhms;" şeklinde bir tanımlama yerine "private Date generationTimestamp;" kullanılmalıdır.

- Sabit, nümerik veya string değerler constant değişkenlerde tutulmalıdır. Örneğin; \
public static final int CONSTANT_INTEGER = 5;\
public static final String CONSTANT_STRING = "some constant";
