
<link href="style.css" rel="stylesheet" id="bootstrap-css">
<link rel="stylesheet" href="custom.css">
<script src="jquery.min.js"></script>
<!------ Include the above in your HEAD tag ---------->
<div id="invoice">
    <div class="result" id="myfrm">
        <div class="invoice overflow-auto">
            <div class="test">
                <center>CERTIFICATE FOR ADDHAAR ENROLMENT/ UPDATE</center>
            </div>
            <div class="row contacts">
                <div class="col invoice-to">
                    <div class="text-gray-light"><span class="bold">Instructions: </span>All details to be filled in block Letters.</span>
                    </div>
                </div>
                <div class="col invoice-details">
                    <span>To be Valid for 3 monthsfrom the date of issue</span>
                </div>
            </div>
            <div class="row contacts">
                <div class="col invoice-to">
                    <div class="text-gray-light italic">To Be printed on Plan A4 Paper size.</div>
                </div>
                <div class="col invoice-details">
                    <span class="italic">Not required to print on letter head</span>
                </div>
                <div class="col invoice-details">
                    <input type="text" id="text2" maxlength="2" placeholder="DD" /> <input type="text" id="text2" maxlength="2" placeholder="MM" /> <input type="text" id="text3" maxlength="4" placeholder="YYYY" />
                </div>
            </div>
            <div class="test">
                <center>Resident's Details</center>
            </div>
            <br>
            <div class="tabbable-line tabbable-full-width">

                <div class="row form-group">
                    <div class="col-md-2">


                    </div>
                    <div class="col-md-2">
                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                        <label class="control-label">Resident.</label>

                    </div>
                    <div class="col-md-3">
                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                        <label class="control-label"> Non-Resident Indian(NRI).</label>
                    </div>
                    <div class="col-md-2">
                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                        <label class="control-label">New Enrolement.</label>
                    </div>
                    <div class="col-md-2">
                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                        <label class="control-label">Update Request.</label>

                    </div>
                </div>
                <div class="tab-content">
                    <div id="tab_2_2" class="tab-pane active">
                        <div class="row">
                            <div class="col-md-12">
                                <div class="booking-search">

                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Aadhaar Number: <br> </span>(For Update Only)</label>
                                        </div>
                                        <div class="col-md-9">
                                            <div class="input-icon">
                                                <input type="text" class="text" id="aadharno" maxlength="12" />
                                            </div>
                                        </div>
                                    </div>

                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Full Name:</span></label>

                                        </div>
                                        <div class="col-md-9">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                                <br>
                                                <br>
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>



                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">C/O:</span></label>

                                        </div>
                                        <div class="col-md-9">

                                            <div class="input-icon">
                                                <input type="text" class="texts" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">House No./Bldg./Apt:</span></label>

                                        </div>
                                        <div class="col-md-9">

                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Street./Road./Lane:</span></label>

                                        </div>
                                        <div class="col-md-9">

                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Landmark:</span></label>

                                        </div>
                                        <div class="col-md-9">

                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Area./Locality./Sector:</span></label>
                                        </div>
                                        <div class="col-md-9">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Village./Town./City:</span></label>
                                        </div>
                                        <div class="col-md-9">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Post Office:</span></label>
                                        </div>
                                        <div class="col-md-9">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">District:</span></label>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="input-icon">
                                                <input type="text" maxlength="25" id="text1" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">State:</span></label>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="25" id="text1" />

                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Pin Code:</span></label>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="25" id="pincode" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Contact Number:</span></label>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="25" id="mobileno" />
                                            </div>
                                        </div>
                                    </div>

                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Date Of Birth:</span></label>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="input-icon">
                                                <!-- <input type="text" class="text" maxlength="25" id="text1" /> -->
                                                <input type="text" id="text2" maxlength="2" placeholder="DD" /> <input type="text" id="text2" maxlength="2" placeholder="MM" /> <input type="text" id="text3" maxlength="4" placeholder="YYYY" />
                                            </div>
                                        </div>
                                        <div class="col-md-2">
                                            <div class="square">
                                                <span style="font-weight:bold;font-size:10px; "><br><br><br><br><br><br><center>Signature Of the Resident/Thumb/Finger Impression.</center></span>
                                            </div>
                                        </div>

                                        <div class="col-md-2">
                                            <div class="square1">
                                                <span style="font-size:10px;"><br><center>Resident's Recent <br>Color Photograph</center></span><span style="color:#000;font-size:12px; font-weight: bold;text-align:center;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;3.5CM X 4.5CM</span>
                                                <span style="font-weight:bold;font-size:10px;"><br>
                                                    <center>Cross Signed and <br>Cross Stamped <br>by the Certifier.</center>
                                                    </span> <span style="font-weight:bold;font-size:10px;"><br><center>NB:DO NOT <br>OVERLAP WITH<br>TEXT BOXES.</center></span>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="test">

                                        <center>Certifier's Details:-(To be Filled by the certifier only).</center>


                                    </div>
                                    <br>


                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Name Of the Certifier:</span></label>

                                        </div>
                                        <div class="col-md-9">

                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="300" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Designation:</span></label>

                                        </div>
                                        <div class="col-md-9">

                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="150" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Address:</span></label>

                                        </div>
                                        <div class="col-md-9">

                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="150" id="text" />
                                            </div>
                                        </div>
                                    </div>
                                    <div class="row form-group">
                                        <div class="col-md-2">
                                            <label class="control-label"><span style="font-weight:bold">Contact Number:</span></label>
                                        </div>
                                        <div class="col-md-4">
                                            <div class="input-icon">
                                                <input type="text" class="text" maxlength="11" id="mobileno" />
                                            </div>
                                        </div>
                                    </div>

                                    <div class="row form-group">
                                        <div class="col-md-8">
                                            <label class="control-label"><span style="font-weight:bold;font-size:13px;">I hereby Certify above mentioned details of the resident<br> and I am a....</span>(The appropriate box below)</label>
                                        </div>
                                    </div>

                                    <div class="row form-group">
                                        <div class="col-md-6">
                                            <li><input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                                                <label class="control-label"><span>Gazetted Officer + Group A:</span></label>
                                            </li>
                                            <li style="hidden=hidden"><input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">

                                                <label class="control-label"><span>Village Panchayat Head Or Mukhiya:</span></label></li>

                                            <li><input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">

                                                <label class="control-label"><span>Gazetted Officer + Group B:</span></label></li>
                                            <li><input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">

                                                <label class="control-label"><span>MP/MLAI/MLC Munciple Councller:</span></label></li>
                                            <li><input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">

                                                <label class="control-label"><span>Tehsildar:</span></label></li>
                                            <li><input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">

                                                <label class="control-label"><span>Head of Recognized Educational Institution:</span></label></li>
                                            <li><input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">

                                                <label class="control-label"><span>Suprintendant / Wardon/ Metron/ Head of Institution <br>of recognized shelter homes/Orphanages:</span></label></li>
                                        </div>

                                        <div class="square2">
                                            <center>
                                                <h6 style="font-weight:400px">Checklist for Certifier
                                                    <center>
                                                </h6>
                                                <div class="row form-group">

                                                    <div class="col-md-3">
                                                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                                                        <label class="control-label" style="font-size:12px;">No Overwriting</label>
                                                    </div>
                                                    <div class="col-md-3">
                                                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                                                        <label class="control-label" style="font-size:12px;">Issue Date is filled</label>
                                                    </div>
                                                    <div class="col-md-3">
                                                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                                                        <label class="control-label" style="font-size:12px;">Resident's signature</label>
                                                    </div>
                                                    <div class="col-md-3">
                                                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                                                        <label class="control-label" style="font-size:12px;">Certifier's Details</label>
                                                    </div>
                                                    <div class="col-md-8 sign">
                                                        <input name="checkbox" class="checkbox1" type="checkbox" id="checkbox" value="">
                                                        <label class="control-label" style="font-size:11px;">Resident's photo is cross and stamped(paper to photo or photo to paper)</label>
                                                    </div>
                                                    <div class="col-md-2">
                                                        <div class="square3">
                                                            <span style="font-weight:bold;font-size:10px;"><center class="signature">Signature & Stamp of the Certifier</center></span>
                                                        </div>
                                                    </div>
                                                </div>
                                        </div>
                                    </div>
                                </div>
                                <!-------------div end--------------->
                            </div>
                        </div>
                        <!--end booking-search-->
                    </div>
                    <!--end col-md-4-->
                </div>
            </div>

            Note:This format is applicable PDI documents at 51.Nos.17,20,21,22,23 & 31;POA documents at 51 Nos.23,2437,38 & 44,POR documents at SI.Nos. 13 &14 DOB documents at 51.Nos.4,5 & 14 of scheduled II of the Aadhaar( Enrolement and Update) Regulations,2016
            as amended from time to time.

            <div class="toolbar hidden-print">
                <div class="text-right">
                    <button id="printInvoice" class="btn btn-info"><i class="fa fa-print"></i> Print</button>

                </div>

            </div>
            <!--DO NOT DELETE THIS div. IT is responsible for showing footer always at the bottom-->
            <div id="note" class="btn" style="font-size:20px;font-weight:bold,color:red;">
                <center>
                    <a href="https://user-images.githubusercontent.com/43174699/103300843-e0c22f80-4a25-11eb-9ca5-76a7b1dcb27a.gif" target="brank_">Help Video</a>
                </center>
                <center>How to print Form: 1&#41; Fill all relevant data in form. 2&#41; After filled form click to print button, print form will popup click background graphics option from print option.</center>
            </div>
        </div>
    </div>

</div>

<script>
    window.alert("Use Google Chrome Only !\n\n फक्त गूगल क्रोम वापरा !\n\nगूगल क्रोम इस्तमाल करे !")
    $('#printInvoice').click(function() {
        Popup($('.invoice')[0].innerHTML);

        function Popup(data) {
            var printdata = document.getElementById(myfrm);
            var printbutton = document.getElementById(printInvoice);
            //document.write(printdata.innerHTML);
            window.print();
            printbutton.style.visibility = "hidden";
            return true;
        }
    });
</script>
<!-- function Popup(data) { var printdata = document.getElementById(myfrm); var printbutton = document.getElementById(printInvoice); //document.write(printdata.innerHTML); window.print(); printbutton.style.visibility = "hidden"; return true; } }); -->
</script><!-- The core Firebase JS SDK is always required and must be listed first -->
<script src="/__/firebase/8.2.1/firebase-app.js"></script>

<!-- TODO: Add SDKs for Firebase products that you want to use
     https://firebase.google.com/docs/web/setup#available-libraries -->
<script src="/__/firebase/8.2.1/firebase-analytics.js"></script>

<!-- Initialize Firebase -->
<script src="/__/firebase/init.js"></script>
