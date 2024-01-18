# Email_Html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Paypal Receipt</title>
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;900&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">
</head>
<style>
/* Common Styles */
body {
    font-family: 'Roboto', sans-serif;
    margin: 0;
    padding: 0;
}

/* Responsive Styles */
@media only screen and (max-width: 490px) {
    .container {
        width: 100%;
    }
    .pay_table .price {
        padding-left: 25% !important;
    }
    .pay_table .qty {
        padding-left: 27px !important;
    }
    .pay_table .amount {
        padding-left: 8% !important;
    }
    .pay_table .price_amount {
        padding-left: 7% !important;
    }
    .pay_table .qty_total {
        padding-left: 14% !important;
    }
    .pay_table .price_usd {
        padding-left: 6% !important;
    }
    .pay_table .total {
        padding-right: 8px !important;
    }
}

@media only screen and (max-width: 360px) {
    .container {
        width: 100%;
    }
    .pay_table .price {
        padding-left: 23% !important;
    }
    .pay_table .qty {
        padding-left: 27px !important;
    }
    .pay_table .amount {
        padding-left: 8% !important;
    }
    .pay_table .price_amount {
        padding-left: 5% !important;
    }
    .pay_table .qty_total {
        padding-left: 13% !important;
    }
    .pay_table .price_usd {
        padding-left: 6% !important;
    }
    .pay_table .total {
        padding-right: 8px !important;
    }
}

/* Email Specific Styles */
body {
    background-color: #A0A0A0;
}

.container {
    max-width: 602px;
    margin: 0 auto;
    background-color: #ffffff;
}

.top_table {
    padding: 15px 20px;
    margin-bottom: 25px;
}

.top_table a {
    max-width: 120px;
    width: 100%;
    height: 0;
}

.top_table i {
    font-size: 30px;
    color: #002F86;
}

.top_table span {
    font-family: sans-serif;
    font-size: 25px;
    font-weight: bold;
    vertical-align: bottom;
    color: #002F86;
    font-style: italic;
}

.top_table span span {
    color: #009CDE;
}

.banner_table img {
    width: 100%;
}

.pay_table {
    padding: 0 20px 25px 20px;
}

.pay_table .description,
.pay_table .price,
.pay_table .qty,
.pay_table .amount {
    font-family: 'Roboto', sans-serif;
    font-size: 11px;
    font-weight: 500;
    color: #808080;
    line-height: 1.9;
}

.pay_table .email {
    font-size: 11px;
    font-weight: 500;
    color: #808080;
    line-height: 1.9;
    padding-left: 10px;
}

.pay_table .price_amount {
    font-size: 11px;
    font-weight: 500;
    color: #808080;
    line-height: 1.9;
    padding-left: 150px;
}

.pay_table .qty_total {
    font-size: 11px;
    font-weight: 500;
    color: #808080;
    line-height: 1.9;
    padding-left: 65px;
}

.pay_table .price_usd {
    font-size: 11px;
    font-weight: 500;
    color: #808080;
    line-height: 1.9;
    padding-left: 107px;
}

.pay_table .total {
    font-size: 12px;
    font-weight: 500;
    color: #222222;
    line-height: 1.9;
    padding-left: 190px;
    padding-right: 10px;
}

.footer_table {
    padding-top: 20px;
    padding-right: 20px;
    padding-bottom: 15px;
    padding-left: 20px;
}

.footer_table span,
.footer_table p {
    font-family: 'Roboto', sans-serif;
    font-size: 12px;
    font-weight: 500;
    color: #222222;
    line-height: 1.9;
    padding-right: 150px;
}

.footer_table i {
    font-size: 15px;
    vertical-align: bottom;
    padding-right: 3px;
    padding-top: 15px;
}

.copyright_table {
    background-color: #A0A0A0;
    padding-top: 20px;
}

.copyright_table p {
    font-size: 11px;
    font-weight: 400;
    color: #222222;
    padding-right: 20px;
    padding-left: 20px;
    line-height: 2;
}
</style>
<body>
    <!-- Start of HTML Email -->
    <table cellpadding="0" cellspacing="0" width="100%">
        <!-- Start of container -->
        <tr>
            <td>
                <table class="container" cellpadding="0" cellspacing="0" align="center">
                    <!-- Start of top area -->
                    <tr>
                        <td>
                            <table class="top_table" cellpadding="0" cellspacing="0" align="center">
                                <!-- ... Rest of the top area ... -->
                            </table>
                        </td>
                    </tr>
                    <!-- End of top area -->
                    <!-- Start of banner area -->
                    <tr>
                        <td>
                            <table class="banner_table" cellpadding="0" cellspacing="0" align="center">
                                <!-- ... Rest of the banner area ... -->
                            </table>
                        </td>
                    </tr>
                    <!-- End of banner area -->
                    <!-- Start of payment -->
                    <tr>
                        <td>
                            <table class="pay_table" cellpadding="0" cellspacing="0" align="center">
                                <!-- ... Rest of the payment area ... -->
                            </table>
                        </td>
                    </tr>
                    <!-- End of payment -->
                    <!-- Start of footer -->
                    <tr>
                        <td align="left" valign="top">
                            <table class="footer_table" cellpadding="0" cellspacing="0" align="center">
                                <!-- ... Rest of the footer area ... -->
                            </table>
                        </td>
                    </tr>
                    <!-- End of footer -->
                    <!-- Start of copyright -->
                    <tr>
                        <td>
                            <table class="copyright_table" cellpadding="0" cellspacing="0" align="center">
                                <!-- ... Rest of the copyright area ... -->
                            </table>
                        </td>
                    </tr>
                    <!-- End of copyright -->
                </table>
            </td>
        </tr>
        <!-- End of container -->
    </table>
    <!-- End of HTML Email -->
</body>
</html>
