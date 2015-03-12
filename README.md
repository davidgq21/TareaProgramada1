# TareaProgramada1
Proyecto 1 Estructura de datos
package tareaprogramada1;

import javax.swing.ImageIcon;

/**
 *
 * @author User
 */
public class Cartas {
    private String descripcion;
    private  ImageIcon imagen;

    public void setDescripcion(String descripcion) {
        this.descripcion = descripcion;
    }

    public void setImagen(ImageIcon imagen) {
        this.imagen = imagen;
    }

    public String getDescripcion() {
        return descripcion;
    }

    public ImageIcon getImagen() {
        return imagen;
    }
    
}
