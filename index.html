<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Logistics Transport System</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial,sans-serif;
}

body{
    background:#f4f7fc;
}

header{
    background:#0d6efd;
    color:white;
    padding:20px;
    text-align:center;
}

.container{
    width:90%;
    max-width:1200px;
    margin:20px auto;
}

.card{
    background:white;
    padding:20px;
    border-radius:12px;
    box-shadow:0 2px 10px rgba(0,0,0,.1);
    margin-bottom:20px;
}

h2{
    margin-bottom:15px;
}

input,select{
    width:100%;
    padding:12px;
    margin:8px 0;
    border:1px solid #ccc;
    border-radius:8px;
}

button{
    background:#0d6efd;
    color:white;
    border:none;
    padding:12px 20px;
    border-radius:8px;
    cursor:pointer;
}

button:hover{
    background:#0b5ed7;
}

table{
    width:100%;
    border-collapse:collapse;
}

table th,table td{
    padding:12px;
    border-bottom:1px solid #ddd;
    text-align:left;
}

.status{
    padding:6px 12px;
    border-radius:20px;
    color:white;
    font-size:14px;
}

.pending{
    background:orange;
}

.transit{
    background:#0d6efd;
}

.delivered{
    background:green;
}

@media(max-width:768px){
    table{
        font-size:14px;
    }
}
</style>
</head>
<body>

<header>
    <h1>🚚 Logistics Management System</h1>
</header>

<div class="container">

    <div class="card">
        <h2>Create Shipment</h2>

        <input type="text" id="customer" placeholder="Customer Name">
        <input type="text" id="pickup" placeholder="Pickup Location">
        <input type="text" id="delivery" placeholder="Delivery Location">

        <select id="status">
            <option value="Pending">Pending</option>
            <option value="In Transit">In Transit</option>
            <option value="Delivered">Delivered</option>
        </select>

        <button onclick="addShipment()">Add Shipment</button>
    </div>

    <div class="card">
        <h2>Shipment Tracking</h2>

        <table>
            <thead>
                <tr>
                    <th>ID</th>
                    <th>Customer</th>
                    <th>Pickup</th>
                    <th>Delivery</th>
                    <th>Status</th>
                </tr>
            </thead>

            <tbody id="shipmentTable"></tbody>
        </table>
    </div>

</div>

<script>
let shipments = [];
let shipmentId = 1;

function addShipment(){

    const customer =
        document.getElementById("customer").value;

    const pickup =
        document.getElementById("pickup").value;

    const delivery =
        document.getElementById("delivery").value;

    const status =
        document.getElementById("status").value;

    if(!customer || !pickup || !delivery){
        alert("Please fill all fields");
        return;
    }

    shipments.push({
        id: shipmentId++,
        customer,
        pickup,
        delivery,
        status
    });

    renderShipments();

    document.getElementById("customer").value="";
    document.getElementById("pickup").value="";
    document.getElementById("delivery").value="";
}

function renderShipments(){

    const table =
        document.getElementById("shipmentTable");

    table.innerHTML="";

    shipments.forEach(item => {

        let className = "pending";

        if(item.status === "In Transit"){
            className = "transit";
        }

        if(item.status === "Delivered"){
            className = "delivered";
        }

        table.innerHTML += `
        <tr>
            <td>${item.id}</td>
            <td>${item.customer}</td>
            <td>${item.pickup}</td>
            <td>${item.delivery}</td>
            <td>
                <span class="status ${className}">
                    ${item.status}
                </span>
            </td>
        </tr>
        `;
    });
}
</script>

</body>
</html>
