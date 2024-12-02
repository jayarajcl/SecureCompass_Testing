<%@ page language="java" contentType="text/html; charset=UTF-8" pageEncoding="UTF-8"%>
<!DOCTYPE html>
<html>
<head>
    <title>Bank Transfer</title>
</head>
<body>
    <h2>Transfer Funds</h2>
    <form action="BankTransfer" method="post">
        <label for="account">Account Number:</label>
        <input type="text" id="account" name="account"><br><br>
        <label for="amount">Amount:</label>
        <input type="text" id="amount" name="amount"><br><br>
        <input type="submit" value="Transfer">
    </form>
</body>
</html>

import javax.servlet.http.HttpServletRequest;

public class BankTransfer {
    public void doPost(HttpServletRequest request) {
        String account = request.getParameter("account");
        String amount = request.getParameter("amount");
        // Perform transfer without verifying CSRF token
    }
}
