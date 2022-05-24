# reactproject
import React from "react";

class Home extends React.Component{

    render(){
        return(
        <>
          <div>
         <h1>STEP 2/5 (Eligibility Matrix)</h1>
	<center>
		<p><input type="checkbox" 
	
				onChange={this.onChange}
		    
			/>
			SELECT ALL BRANCHES AND PROGRAMMES COMING FROM JEE ADVANCED<br/>
			<input type="checkbox"/>
		   SELECT ALL BRANCHES AND PROGRAMMES COMING FROM GATE<br/>
		   <input type="checkbox"/>
		   SELECT ALL BRANCHES AND PROGRAMMES COMING FROM JAM <br/>
		   <input type="checkbox"/>
		   SELECT ALL BRANCHES AND PROGRAMMES COMING FROM CAT</p>
		   <table>
		   	<tr>
		   		<th>Program </th>
		   		<th>All </th>
		   		<th>AE </th>
		   		<th>BSBE </th>
		   		<th>CE </th>
		   		<th>CHE </th>
		   		<th>CSE </th>
		   		<th>EE </th>
		   		<th>ES </th>
		   		<th>ME </th>
		   		<th>MSE </th>
		   		<th>PHY </th>
		   		<th>CHM </th>
		   		<th>MTH </th>
		   		<th>ECO </th>
		   		<th>DES </th>
		   		<th>IME </th>
		   		<th>CGS </th>
		   		<th>HSS </th>
		   		<th>EEM </th>
		   		<th>MSP </th>
		   		<th>NET </th>
		   		<th>PSE </th>
		   		<th>STATS </th>
		   	</tr>
		   	<tr>
		   		<td>BT/BS/Double Major</td>
		   		<td><input type="checkbox"	/></td>
		   		<td><input type="checkbox"         
				onChange={this.onChange}	/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   	</tr>
		   	<tr>
		   		<td>MT/MSc/MS(Research)</td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   	</tr>
		   	<tr>
		   		<td>Dual</td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   	</tr>
		   		<tr>
		   		<td>MDes</td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   	</tr>
		   		<tr>
		   		<td>MBA</td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   	</tr>
		   		<tr>
		   		<td>Phd</td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   		<td><input type="checkbox"/></td>
		   	</tr>
		   </table>
		   <table>
		   	<tr >
		   		<th>AE AEROSPACE ENGINEERING</th>
		   		<th>BSBE BIOLOGICAL SCIENCES AND BIOENGINEERING</th>
		   		<th>CE CIVIL ENGINEERING</th>
		   	</tr>
		   	<tr >
		   		<th>CHE CHEMICAL ENGINEERING</th>
		   		<th>CSE COMPUTER SCIENCE AND ENGINEERING</th>
		   		<th>EE ELECTRICAL ENGINEERING</th>
		   	</tr>
		   	<tr >
		   		<th>ES EARTH SCIENCES</th>
		   		<th>ME MECHANICAL ENGINEERING</th>
		   		<th>MSE MATERIAL SCIENCE AND ENGINEERING</th>
		   	</tr>
		   	<tr >
		   		<th>PHY PHYSICS</th>
		   		<th>CHM CHEMISTRY</th>
		   		<th>MTH MATHEMATICS AND SCIENTIFIC COMPUTING</th>
		   	</tr>
		   	<tr >
		   		<th>ECO ECONOMICS</th>
		   		<th>DES DESIGN PROGRAM</th>
		   		<th>IME INDUSTRIAL MANAGEMENT AND ENGINEERING</th>
		   	</tr>
		   	<tr >
		   		<th>CGS CONGINTIVE SCIENCES</th>
		   		<th>HSS HUMANITIES AND SOCIAL SCIENCES</th>
		   		<th>EEM ENVIRONMENTAL ENGINEERING AND MANAGEMENT</th>
		   	</tr>
		   	<tr >
		   		<th>MSP MATERIAL SCIENCE PROGRAM</th>
		   		<th>NET NUCLEAR ENGINEERING AND TECHNOLOGY</th>
		   		<th>PSE PHOTONICS SCIENCE AND ENGINEERING</th>
		   	</tr>
		   	<tr >
		   		<th>STATS STATISTICS</th>
		   		<th></th>
		   		<th></th>
		   	</tr>
         </table>
         
  </center>
<p>FOR MORE DETAILS ABOUT ACADEMIC PROGRAMMES CLICK HERE<input type="checkbox"/><br/>
    RESET 
    <button type="reset" value="Reset">Reset</button></p>
        </div>
        </>
        );
    }
}

export default Home;
