# ĐỀ THI TRẮC NGHIỆM ÔN TẬP - AN TOÀN VÀ BẢO MẬT THÔNG TIN
## NỘI DUNG: CHƯƠNG 1 ĐẾN CHƯƠNG 6

---

### **PHẦN CÂU HỎI TRẮC NGHIỆM**

**Câu 1:** Bản rõ $x = 15$, khóa công khai với modulo hệ thống $N = 39, e = 7$. Khi mã hóa bản rõ $x$ với khóa trên theo hệ RSA, chúng ta sẽ thu được bản mã nào sau đây:
* A. $32$
* B. $24$
* C. $65$
* D. $14$

**Câu 2:** Vectơ khởi tạo (IV) **không** được sử dụng trong chế độ nào sau đây:
* A. MAC
* B. CFB
* C. OFB
* D. CBC

**Câu 3:** Trong hệ trao đổi khóa Diffie-Hellman với $p = 11, \alpha = 5$. Khi người A tính được $S_A = 4$ và gửi cho người B, người B chọn số ngẫu nhiên (bí mật) $r_B = 7$. Khi đó người B tính được khóa chung $K$ là:
* A. $K = 11^7 \bmod 5$
* B. $K = 4^5 \bmod 11$
* C. $K = 4^7 \bmod 11$
* D. $K = 4^{11} \bmod 5$

**Câu 4:** AES được chuẩn hóa bởi tổ chức nào:
* A. ITU
* B. IEEE
* C. NIST
* D. ISO

**Câu 5:** Chế độ liên kết khối mã CBC có nhược điểm lớn nhất là gì:
* A. Tốc độ thực hiện chậm
* B. Không sử dụng Vectơ khởi tạo (IV)
* C. Lỗi bị lan truyền khi truyền tin
* D. Dễ bị tấn công phân tích mật mã

**Câu 6:** Mã dịch vòng (Shift Cipher) thuộc loại mã nào sau đây:
* A. Tất cả các phương án đều đúng
* B. Mã thay thế đa biểu (Polyalphabetic Substitution)
* C. Mã hóa khóa công khai
* D. Mã thay thế đơn biểu (Monoalphabetic Substitution)

**Câu 7:** Phát biểu nào sau đây là **đúng** khi nói về hệ mã khóa công khai:
* A. Tất cả các phương án đều sai
* B. Dùng chung 1 khóa để mã hóa và giải mã
* C. Có thể dùng khóa công khai (public key) của người nhận để mã hóa dữ liệu gửi đi
* D. Có thể dùng khóa công khai (public key) của người gửi để mã hóa dữ liệu gửi đi

**Câu 8:** Trong 4 chế độ ứng dụng của chuẩn DES, các chế độ hoạt động theo kiểu mã dòng (Stream Cipher) là:
* A. Chế độ phản hồi mã CFB (Cipher Feedback) và chế độ phản hồi đầu ra OFB (Output Feedback)
* B. Chế độ bản mã điện tử ECB (Electronic Codebook) và chế độ phản hồi đầu ra OFB (Output Feedback)
* C. Chế độ phản hồi mã CFB (Cipher Feedback) và chế độ liên kết khối mã CBC (Cipher Block Chaining)
* D. Chế độ bản mã điện tử ECB (Electronic Codebook) và chế độ liên kết khối mã CBC (Cipher Block Chaining)

**Câu 9:** Một hệ thống gồm 10 thiết bị đầu cuối liên lạc với nhau sử dụng mật mã đối xứng. Mỗi đầu cuối sử dụng các khóa bí mật khác nhau khi kết nối với mỗi đầu cuối khác. Có bao nhiêu khóa bí mật cần dùng trong toàn bộ hệ thống:
* A. 10 khóa
* B. 45 khóa
* C. 90 khóa
* D. 20 khóa

**Câu 10:** Khi so sánh hệ mật mã RSA và DES, phát biểu nào sau đây là chính xác nhất:
* A. RSA dựa trên các hàm toán học phức tạp, còn DES dựa trên các thao tác xử lý bit (thay thế và hoán vị)
* B. RSA luôn an toàn tuyệt đối hơn so với DES trong mọi trường hợp
* C. Bằng cách phân tích khóa công khai có thể tìm ra ngay khóa bí mật của RSA, trong khi đối với DES bắt buộc phải thử khóa vét cạn
* D. RSA có tốc độ thực thi bằng phần mềm cao hơn nhiều so với DES

**Câu 11:** Trong hệ RSA, cho số mũ công khai $e = 23$ và giá trị hàm Euler $\Phi(N) = 160$. Số nghịch đảo $d$ (khóa bí mật) của $e$ là:
* A. $d = 1$ vì $d \cdot e = 1$
* B. Không thể tìm được số nghịch đảo thỏa mãn
* C. $d = 7$ vì $23$ chia hết cho $7$
* D. $d = 7$ vì $23 \cdot 7 = 161 \equiv 1 \pmod{160}$

**Câu 12:** Phương thức tấn công nào ngăn chặn các người dùng hợp lệ truy xuất và sử dụng các tài nguyên của hệ thống:
* A. Tấn công nghe trộm (Sniffing)
* B. Tấn công giả mạo (Spoofing)
* C. Tấn công từ chối dịch vụ (DoS)
* D. Tấn công kẻ đứng giữa (Man-In-The-Middle)

**Câu 13:** Giá trị của hàm Euler $\phi(440)$ bằng bao nhiêu:
* A. 160
* B. 44
* C. 234
* D. 110

**Câu 14:** Một trong hai cách tiếp cận cơ bản nhất để tấn công hệ mật mã đối xứng là:
* A. Không thể thực hiện tấn công
* B. Tấn công tìm khóa dựa trên khóa công khai
* C. Tấn công tìm bản rõ trực tiếp
* D. Tấn công duyệt toàn bộ khóa (vét cạn / brute-force)

**Câu 15:** Chọn câu **sai** khi nói về nguy cơ đối với sự an toàn của hệ thống thông tin:
* A. Việc xâm nhập hệ thống (intrusion) có thể xuất phát từ cả bên ngoài lẫn bên trong hệ thống
* B. Tin tặc (Attacker) chỉ có thể là người từ bên ngoài hệ thống
* C. Người sử dụng không được huấn luyện về an toàn hệ thống cũng là một nguy cơ lớn
* D. Hệ thống không kết nối Internet thì hoàn toàn không có nguy cơ bị tấn công

**Câu 16:** Trong hệ RSA, biết khóa bí mật $d = 7$, các số nguyên tố $p = 5, q = 11$ và nhận được bản mã $C = 5$. Bản rõ $M$ được tính toán theo công thức nào sau đây:
* A. $M = C^d \bmod 55 = 5^7 \bmod 55$
* B. $M = C^p \bmod 55 = 5^5 \bmod 55$
* C. $M = d^C \bmod 40 = 7^5 \bmod 40$
* D. $M = C^d \bmod 40 = 5^7 \bmod 40$

**Câu 17:** Trong hệ mật mã hóa khóa công khai RSA, biết hai số nguyên tố $p = 5, q = 7$. Giá trị của hàm phi Euler $\Phi(N)$ là:
* A. Một số khác
* B. 24
* C. 12
* D. 35

**Câu 18:** Biểu thức mã hóa được viết dưới dạng $X = E_K(Y)$. Trong đó, bản mã thu được là ký hiệu nào:
* A. $K$
* B. $Y$
* C. $X$
* D. $D$

**Câu 19:** Nguyên tắc cơ bản nhất khi xây dựng một hệ thống bảo mật an toàn thông tin là gì:
* A. Áp dụng các cơ chế bảo mật phù hợp với quy mô hệ thống
* B. Tất cả các phương án đều đúng
* C. Thiết lập và xây dựng các chính sách bảo mật chặt chẽ
* D. Xây dựng các chính sách bảo mật rõ ràng kết hợp triển khai các cơ chế kỹ thuật để đảm bảo thực thi chính sách đó

**Câu 20:** Chọn câu **sai** khi nói về chuẩn mã hóa nâng cao AES:
* A. AES là thuật toán mã hóa có độ an toàn thấp hơn DES
* B. Tất cả các phát biểu đều đúng
* C. AES là chuẩn mã hóa ra đời sau và nâng cao hơn DES
* D. AES là chuẩn mã hóa khối đối xứng có hiệu năng và độ bảo mật cao

**Câu 21:** Bản mã hóa Caesar (với khóa dịch chuyển $k = 3$) của từ khóa "party" là:
* A. sduwb
* B. tduwb
* C. Tất cả đều sai
* D. teuwb

**Câu 22:** Phát biểu nào sau đây là **sai** khi nói về hệ thống xác thực Kerberos:
* A. Tất cả các phương án đều sai
* B. Kerberos có thể bị tấn công đoán mật khẩu (Password Guessing) nếu mật khẩu yếu
* C. Kerberos vẫn có nguy cơ bị tấn công trong một số điều kiện môi trường cụ thể
* D. Kerberos đáp ứng đầy đủ yêu cầu chống chối cãi (Non-repudiation)

**Câu 23:** Chọn phát biểu **đúng** khi nói về khái niệm nguy cơ (threat) và rủi ro (risk) đối với hệ thống thông tin:
* A. Tất cả các rủi ro đều có ít nhất một nguy cơ đi kèm với nó
* B. Có thể triệt tiêu hoàn toàn rủi ro bằng cách ngăn chặn các nguy cơ tương ứng
* C. Mục tiêu tối thượng của bảo mật hệ thống là ngăn chặn tất cả mọi rủi ro có thể xảy ra trên hệ thống
* D. Tất cả các câu trên đều đúng

**Câu 24:** Trong thuật toán mã hóa DES, hàm vòng $f$ (Round Function) gồm bao nhiêu bước biến đổi chính:
* A. 2 bước
* B. 3 bước
* C. 4 bước (Mở rộng bit, Cộng khóa K, Thay thế S-box, Hoán vị P-box)
* D. 5 bước

**Câu 25:** Trong thuật toán mã hóa cổ điển Hill, dữ liệu đầu vào được xử lý dưới dạng nào:
* A. Từng ký tự riêng lẻ
* B. Theo từng từ ngữ
* C. Theo từng cặp hoặc khối ký tự (sử dụng ma trận)
* D. Theo từng dòng văn bản

**Câu 26:** Trong hệ trao đổi khóa Diffie-Hellman với số nguyên tố $p = 11, \alpha = 5$. Người A chọn số ngẫu nhiên bí mật $r_A = 3$. Khi đó, giá trị công khai $S_A$ do người A tính toán và gửi đi là:
* A. $S_A = 1$
* B. $S_A = 4$
* C. $S_A = 15$
* D. $S_A = 2$

**Câu 27:** Các hộp thay thế S-box trong giải thuật DES thực hiện chức năng nào sau đây:
* A. Hoán vị vị trí các bit
* B. Thay thế phi tuyến tính các nhóm bit để tạo tính hỗn loạn (confusion)
* C. Sinh khóa vòng và mã hóa khóa
* D. Giải mã dữ liệu khối

**Câu 28:** Khi nhắc đến hệ mã hóa khóa công khai (mật mã bất đối xứng), phát biểu nào dưới đây là chính xác:
* A. Tất cả các câu đều sai
* B. Hệ thống sử dụng một cặp khóa: một khóa để mã hóa (khóa công khai) và một khóa khác để giải mã (khóa bí mật)
* C. Không thể bị tấn công bằng phương pháp duyệt khóa vét cạn
* D. Chỉ có thể dùng duy nhất khóa công khai để thực hiện mã hóa thông tin bảo mật

**Câu 29:** Các cơ chế cơ bản nhằm đảm bảo tính toàn vẹn (Integrity) của thông tin bao gồm:
* A. Lưu trữ toàn bộ dữ liệu trong hệ thống dưới dạng tệp tin nén
* B. Tất cả các cơ chế nêu trên
* C. Bao gồm các cơ chế ngăn chặn thay đổi trái phép và các cơ chế phát hiện vi phạm tính toàn vẹn dữ liệu
* D. Tiến hành mật mã hóa toàn bộ dữ liệu lưu trữ trong hệ thống

**Câu 30:** Chọn câu **đúng** khi nói về các loại mã độc (malicious code) phá hoại hệ thống:
* A. Worm (sâu máy tính) là loại mã độc bắt buộc phải hoạt động dựa vào việc ký sinh vào một file phần mềm khác
* B. Logic bomb (bom logic) sẽ bị vô hiệu hóa hoàn toàn nếu đồng hồ của hệ thống luôn chạy chậm hơn thời gian thực tế
* C. Trojan horse (ngựa Trojan) là loại mã độc ngụy trang dưới dạng một chương trình hữu ích hoặc các tệp tin bình thường để đánh lừa người dùng
* D. Virus máy tính có khả năng tự động sao chép và tự lan truyền qua mạng máy tính mà không cần bất kỳ sự tương tác nào của người dùng hay vật chủ

**Câu 31:** Chế độ bản mã điện tử ECB (Electronic Codebook) có đặc điểm nổi bật nào:
* A. Việc mã hóa/giải mã các khối dữ liệu diễn ra hoàn toàn độc lập với nhau
* B. Quá trình mã hóa khối hiện tại phụ thuộc chặt chẽ vào khối mật mã trước đó
* C. Đạt mức độ an toàn và bảo mật thông tin rất cao
* D. Có tính an toàn vượt trội hơn hẳn so với thuật toán DES thông thường

**Câu 32:** Đặc điểm nổi bật của hệ mật mã khóa bí mật (khóa đối xứng) so với hệ mật mã khóa công khai là:
* A. Không đảm bảo tính an toàn khi truyền tin trên kênh truyền
* B. Tốc độ tính toán và thực hiện mã hóa/giải mã cực kỳ nhanh chóng
* C. Đang dần bị thay thế hoàn toàn bởi hệ mật mã khóa công khai
* D. Tốc độ thực hiện rất chậm và tốn nhiều tài nguyên hệ thống

**Câu 33:** RSA là thuật toán thuộc loại nào sau đây:
* A. Thuật toán mã hóa khóa bí mật (mật mã đối xứng)
* B. Tất cả các phương án đều sai
* C. Thuật toán mã hóa khóa công khai (mật mã bất đối xứng)
* D. Tên gọi của một tổ chức tiêu chuẩn hóa mật mã quốc tế

**Câu 34:** Phép tính số dư $7^{2023} \bmod 13$ cho kết quả bằng bao nhiêu:
* A. 6
* B. 13
* C. 7
* D. Một số khác

**Câu 35:** Trong hệ RSA, cho số mũ công khai $e = 11$, hai số nguyên tố $p = 5, q = 7$. Khi mã hóa bản rõ $M = 4$, ta thu được bản mã $C$ bằng bao nhiêu:
* A. 9
* B. 35
* C. 4
* D. 24

**Câu 36:** Khẳng định nào sau đây là chính xác đối với thuật toán băm MD5:
* A. Giá trị băm đầu ra luôn có độ dài cố định là 256 bit
* B. Là một thuật toán chuyên dụng để tạo chữ ký số bất đối xứng
* C. Giá trị băm đầu ra luôn có độ dài cố định là 128 bit
* D. Thuộc nhóm các giải thuật mã hóa khóa công khai

**Câu 37:** Chọn nhận định **đúng** khi nói về độ an toàn của chuẩn mật mã DES:
* A. Tất cả các nhận định đều đúng
* B. Các thiết bị giải mã Triple-DES (TDES) không có khả năng tương thích ngược để giải mã dữ liệu mã hóa bằng DES
* C. Khóa đầu vào của DES có độ dài 64 bit, nhưng thực chất thuật toán chỉ sử dụng 56 bit để mã hóa (8 bit còn lại dùng để kiểm tra chẵn lẻ)
* D. Phương pháp duy nhất có khả năng tấn công phá mã hệ thống mật mã DES là tấn công brute-force vét cạn khóa

**Câu 38:** Hộp hoán vị P-box (Permutation Box) trong thuật toán DES được sử dụng với mục đích chính là:
* A. Hoán vị vị trí sắp xếp của các bit dữ liệu
* B. Giải mã ngược dữ liệu đã bị mã hóa
* C. Khởi tạo khóa vòng cho các vòng lặp
* D. Thực hiện mã hóa các khối văn bản

**Câu 39:** Hàm băm không khóa (Hash Function) thường được sử dụng nhằm mục đích chính nào sau đây:
* A. Bảo vệ và kiểm tra tính toàn vẹn của thông tin (Integrity)
* B. Thực hiện giải mã thông tin mật
* C. Xác thực nguồn gốc thực tế của thông tin (Authentication)
* D. Tiến hành mã hóa bảo mật thông tin

**Câu 40:** Nhóm nào dưới đây chứa hoàn toàn các thuật toán mã hóa đối xứng (Symmetric Encryption):
* A. IDEA, Blowfish, AES, Elliptic Curve
* B. Triple-DES, RC4, RC5, IDEA
* C. Triple-DES, RC4, RC5, Blowfish
* D. RC4, RC5, IDEA, Blowfish

---

### **BẢNG ĐÁP ÁN THAM KHẢO (ANSWER KEY)**

| Câu | Đáp án | Giải thích tóm tắt |
| :---: | :---: | :--- |
| **1** | **B** | $y = 15^7 \bmod 39 = 24$. |
| **2** | **A** | MAC (Message Authentication Code) không sử dụng IV trực tiếp như các chế độ mã khối CBC, CFB, OFB. |
| **3** | **C** | Khóa chung $K = S_A^{r_B} \bmod p = 4^7 \bmod 11$. |
| **4** | **C** | AES được chuẩn hóa bởi NIST (Viện Tiêu chuẩn và Công nghệ Quốc gia Mỹ). |
| **5** | **C** | CBC có tính chất lan truyền lỗi (error propagation): lỗi ở 1 bit bản mã làm sai lệch toàn bộ khối bản rõ giải mã tương ứng và bit ở khối tiếp theo. |
| **6** | **D** | Mã dịch vòng (như Caesar) là mã thay thế đơn biểu (mỗi ký tự được thay thế cố định bởi một ký tự khác cách nó $k$ vị trí). |
| **7** | **C** | Mã hóa khóa công khai sử dụng khóa public của người nhận để mã hóa, và người nhận dùng khóa private của mình để giải mã. |
| **8** | **A** | CFB và OFB hoạt động như mã dòng bằng cách tạo ra keystream từ các khối trước đó rồi XOR với bản rõ. |
| **9** | **B** | Công thức tính số khóa đối xứng cho $n$ thiết bị liên lạc đôi một: $\frac{n(n-1)}{2} = \frac{10 \times 9}{2} = 45$ khóa. |
| **10** | **A** | DES/AES dựa trên xử lý bit phi toán học (S-box, P-box), còn RSA dựa trên toán học số học modulo lớn. |
| **11** | **D** | Số nghịch đảo thỏa mãn $e \cdot d \equiv 1 \pmod{\Phi(N)} \implies 23 \cdot 7 = 161 \equiv 1 \pmod{160}$. |
| **12** | **C** | Tấn công từ chối dịch vụ (DoS - Denial of Service) nhằm làm quá tải hệ thống, chặn truy cập hợp lệ. |
| **13** | **A** | $440 = 2^3 \times 5 \times 11 \implies \phi(440) = 440 \times (1 - \frac{1}{2}) \times (1 - \frac{1}{5}) \times (1 - \frac{1}{11}) = 160$. |
| **14** | **D** | Một trong hai cách tiếp cận cơ bản để phá mã đối xứng là Phân tích mật mã (Cryptanalysis) và Thử vét cạn khóa (Brute-force). |
| **15** | **D** | Kể cả không nối mạng Internet, hệ thống vẫn có nguy cơ bị tấn công vật lý, qua cổng USB, mã độc gián điệp hoặc từ nội bộ. |
| **16** | **A** | Công thức giải mã RSA: $M = C^d \bmod N$ với $N = p \cdot q = 5 \times 11 = 55$. Vậy $M = 5^7 \bmod 55$. |
| **17** | **B** | $\Phi(N) = (p-1)(q-1) = (5-1)(7-1) = 4 \times 6 = 24$. |
| **18** | **C** | $X = E_K(Y)$ có nghĩa là Bản mã $X$ là kết quả của hàm mã hóa $E$ dưới khóa $K$ lên bản rõ $Y$. |
| **19** | **D** | Chính sách bảo mật (Policy) định nghĩa mục tiêu, còn cơ chế bảo mật (Mechanism) là công cụ thực thi chính sách đó. Cần có cả hai. |
| **20** | **A** | AES (Advanced Encryption Standard) an toàn hơn DES rất nhiều và được thiết kế để thay thế DES đã bị bẻ khóa. |
| **21** | **A** | Dịch chuyển mỗi chữ cái trong "party" đi 3 vị trí trong bảng chữ cái: p $\to$ s, a $\to$ d, r $\to$ u, t $\to$ w, y $\to$ b. Kết quả: `sduwb`. |
| **22** | **D** | Kerberos dùng mật mã đối xứng nên KDC có khóa của mọi đối tượng, không thể cung cấp tính chống chối cãi (Non-repudiation) như chữ ký số bất đối xứng. |
| **23** | **A** | Rủi ro chỉ xuất hiện khi có sự tồn tại của nguy cơ khai thác lỗ hổng. (Không thể triệt tiêu hoàn toàn rủi ro và mục tiêu bảo mật chỉ là giảm rủi ro xuống mức chấp nhận được). |
| **24** | **C** | Hàm $f$ của DES gồm 4 bước chính: Mở rộng bit (Expansion), Cộng khóa vòng (Key Addition), Hộp thay thế (S-box), Hoán vị (P-box). |
| **25** | **C** | Mã hóa Hill chia bản rõ thành các khối kích thước $m$ ký tự và nhân với ma trận khóa $m \times m$ modulo 26. |
| **26** | **B** | $S_A = \alpha^{r_A} \bmod p = 5^3 \bmod 11 = 125 \bmod 11 = 4$. |
| **27** | **B** | S-box trong DES nhận đầu vào 6 bit, cho đầu ra 4 bit, đóng vai trò là phép biến đổi phi tuyến tính cực kỳ quan trọng tạo độ xáo trộn. |
| **28** | **B** | Bản chất mật mã bất đối xứng là dùng một cặp khóa liên kết toán học: khóa công khai mã hóa và khóa bí mật giải mã. |
| **29** | **C** | Bảo vệ tính toàn vẹn đòi hỏi các cơ chế ngăn chặn sửa đổi (như phân quyền) và phát hiện sửa đổi (như dùng hàm băm, chữ ký số). |
| **30** | **C** | Trojan giả dạng làm phần mềm sạch để lừa người dùng cài đặt. (Worm có thể hoạt động độc lập, Virus cần tệp vật chủ, bom logic kích hoạt theo điều kiện định sẵn). |
| **31** | **A** | Chế độ ECB mã hóa độc lập từng khối dữ liệu với cùng một khóa, dẫn đến việc các khối bản rõ giống nhau sẽ tạo ra các khối bản mã giống nhau. |
| **32** | **B** | Mật mã khóa đối xứng có ưu điểm vượt trội về tốc độ xử lý bit cực nhanh, thường nhanh hơn mã hóa bất đối xứng hàng trăm đến hàng nghìn lần. |
| **33** | **C** | RSA (viết tắt từ tên Rivest, Shamir, Adleman) là thuật toán mã hóa bất đối xứng (khóa công khai) phổ biến nhất thế giới. |
| **34** | **A** | Áp dụng định lý Fermat nhỏ: $7^{12} \equiv 1 \pmod{13}$. Có $2023 = 12 \times 168 + 7 \implies 7^{2023} \equiv 7^7 \equiv 6 \pmod{13}$. |
| **35** | **A** | $C = M^e \bmod N = 4^{11} \bmod 35 = 9$. |
| **36** | **C** | MD5 là hàm băm tạo ra chuỗi hash cố định có độ dài 128 bit (16 bytes). |
| **37** | **C** | Khóa của DES dài 64 bit nhưng có 8 bit kiểm tra chẵn lẻ (parity bits), nên độ dài khóa thực tế tham gia mã hóa chỉ là 56 bit. |
| **38** | **A** | P-box (Permutation box) thực hiện hoán vị xáo trộn vị trí các bit dữ liệu. |
| **39** | **A** | Hàm băm không khóa được dùng để tính toán mã kiểm tra, đảm bảo tệp tin hoặc thông điệp không bị thay đổi trong quá trình truyền (toàn vẹn). |
| **40** | **B/C/D**| Cả 3 phương án B, C, D đều chứa toàn các thuật toán mã hóa đối xứng (Triple-DES, RC4, RC5, IDEA, Blowfish). Riêng phương án A chứa Elliptic Curve là thuật toán bất đối xứng. |
