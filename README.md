# SPRINT2
package sprint2;

import javax.swing.JOptionPane;

public class MOVIMIENTO {
    private String concepto;
    private int ingreso;
    private int egreso;
    private String fecha;
    private String usuario; 
    private float monto;

    public MOVIMIENTO(String concepto, int ingreso, int egreso, String fecha) {
        this.concepto = concepto;
        this.ingreso = ingreso;
        this.egreso = egreso;
        this.fecha = fecha;
    }
    public void monto(){
        monto= ingreso -egreso;
    }
        
    
    public String getConcepto() {
        return concepto;
    }

    public void setConcepto(String concepto) {
        this.concepto = concepto;
    }

    public int getIngreso() {
        return ingreso;
    }

    public void setIngreso(int ingreso) {
        this.ingreso = ingreso;
    }

    public int getEgreso() {
        return egreso;
    }

    public void setEgreso(int egreso) {
        this.egreso = egreso;
    }

    public String getFecha() {
        return fecha; 
    }

    public void setFecha(String fecha) {
        this.fecha = fecha;
    }

    @Override
    public String toString() {
        return "concepto=" + concepto + "\n, fecha=" + fecha + "\n, usuario=" + usuario + "\n, monto=" + monto;
    }

    
   
    }
    
  

