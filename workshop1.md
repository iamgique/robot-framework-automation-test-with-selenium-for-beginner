#Workshop 1
###Facebook Login

**Task**

1.Run robot with facebook-login-success.robot<br />
2.Run robot with facebook-login-more-than-1-scenario.robot<br />
3.Run robot all file<br />
4.Reports<br />

**Login to Facebook Success**

| No | Test Procedure                                                                            | Expected Result       | Test Result | Remark |
|----|-------------------------------------------------------------------------------------------|-----------------------|-------------|--------|
| 1  | Open website Facebook                                                                     | To show Facebook page |             |        |
| 2  | Type your@email.com address to input text. Type password to input password. Submit to login | Login Success         |             |        |
|    |                                                                                           |                       |             |        |

**Login to Facebook more than 1 scenario**

| No | Test Procedure                                                                      | Expected Result                            | Test Result | Remark |
|----|-------------------------------------------------------------------------------------|--------------------------------------------|-------------|--------|
| 1  | Open website Facebook                                                               | To show Facebook page                      |             |        |
| 2  | Type test@t.com address to input text. Type password to input password. Submit to login | อีเมลที่คุณป้อนไม่ตรงกับบัญชีผู้ใช้ใดๆ สมัครใช้งานบัญชีผู้ใช้ |             |        |
| 3  | Type a@a.com address to input text. Type password to input password. Submit to login    | รหัสผ่านที่คุณป้อนไม่ถุกต้อง ลืมรหัสผ่าน?              |             |        |
|    |                                                                                     |                                            |             |        |

![Facebook Login scenario](/images/facebook-login-scenario.png)

![Facebook Login](/images/facebook-login.png)

![Report](/images/facebook-login-report-success.png)
