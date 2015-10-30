# 20151030

                자바가 안됐다고 나왔을 때
                source /etc/profile 쓰면 된다.





•주기적으로 증가하는 데이터를 출력

        vim test.py

                #!/usr/bin/python
                # -*- coding: utf-8 -*- 

                count = 0

                if __name__ == '__main__':

                   while 1 :
                        t = time.localtime()
                        tsec = t.tm_sec

                        if tsec%10!=0 :
                            print tsec
                            time.sleep(0.8)
                        else :
                            print count

