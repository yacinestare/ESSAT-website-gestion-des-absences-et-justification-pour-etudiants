<?php 
include "db_conn.php";


$ide =$_GET['id'];
$mod =$_GET['nommod'];
$idmod =$_GET['idmod']; 
$idspec =$_GET['spec']; 
$idsem =$_GET['sem'];  
 ?>

<!DOCTYPE html>

<html>

<head>

    <title>HOME</title>

    <link rel="stylesheet" type="text/css" href="style.css">

</head>

<body>

     <h1> <?php 
       
       $sql = "SELECT * FROM etudiant  WHERE num_ins_etu='$ide'";
       
      $result = mysqli_query($conn, $sql);
       while($row = mysqli_fetch_assoc($result)) { 
       $nometu= $row['nom_etu'];
       $prenometu= $row['prenom_etu'];
       $datenaissetu= $row['date_nais_etu'];
       echo  'etat absence de : '.$nometu.'  '.$prenometu.' n&eacutee le '.$datenaissetu.' pour le module de '.$mod; 
       }
       ?> </h1>
      

<form action="justification2.php" method="post">
       

<?php
$currentDate = date('Y-m-d'); ?>
<label for="sdate4">veuillez confirmer la date:</label>

<input type="date" id="sdate1" name="sdate1"
       value=<?php echo $currentDate; ?>
     >
       >
<input type="date" id="sdate2" name="sdate2"
       value=<?php echo $currentDate; ?>
     >
       >
<input type="date" id="sdate3" name="sdate3"
       value=<?php echo $currentDate; ?>
     >
       >


   

   

<input type="hidden" name="idetu"  value=<?php echo $ide; ?>  >
<input type="hidden" name="idmod"  value=<?php echo $idmod; ?> >
<input type="hidden" name="sspec"  value=<?php echo $idspec; ?> >
<input type="hidden" name="ssem"   value=<?php echo $idsem; ?> >

<button type="submit" >justifier</button>

</form>








      <table>
       <tr id="id_table">
         <th>date debut de justification</th>
         <th>date de fin </th>
         <th>date  arriver</th>
         <th>justifie </th>
         <th>date de justification </th>
         </tr>
     
        <?php 
        $sql = "SELECT * FROM justification  WHERE num_ins_etu='$ide'";
       
        $req = mysqli_query($conn, $sql);
         while($row = mysqli_fetch_assoc($req)) {
            $nabs=$row['num_abs']; $dabs =$row['date_abs']; $nabas=$row['nature_abs'];
            $sql2 = "SELECT * FROM justification  WHERE num_abs='$nabs'";  
            $req2 = mysqli_query($conn, $sql2);
            $i=0; $djus="";
            while($row2 = mysqli_fetch_assoc($req2)) {
               $djus=$row2['date_arrive_just'];
               $i++; 
            }
             ?>
             <tr  id="id_table">
                <td><?=$nabs?></td>
                <td><?=$dabs?></td>
                <td><?=$nabas?></td>
                <td><?=$i?></td>
                <td><?=$djus?></td>
             </tr>
             <?php 
}

 ?>  
      
      </table>     
           
     <a href="logout.php">Logout</a>

</body>

</html>